---
title: "Specs: Ethereum"
navTitle: "Ethereum"
---

# Ethereum as an IPLD Data Structure

Ethereum can be read and accessed as IPLD data.

Within these documents, schemas are grouped by their serialized blocks.
Other than those types listed in "Basic Types", the top-level schema type in each grouping of schema
types in a code block represents a data structure that is serialized into a single IPLD block with its own Link (CID).

There are some state data structures that are repeats of the same form: a modified merkle patricia trie node.
They are not de-duplicated here for clarity to demonstrate the different purposes and contents of those data structures.

For more information about the IPLD Schema language, see the [IPLD Schema documentation](/docs/schemas/).

## Data Structure Descriptions

* [Ethereum Data Structures **Basic Types**](./basic_types/)
* [Ethereum **Chain** Data Structures](./chain/)
* [Ethereum **Convenience Types**](./convenience_types/)
* [Ethereum **State** Data Structures](./state/)
