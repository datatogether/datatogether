The Data Together Model
========

_This page is an incomplete work in progress. Seeking Pull Requests to help us refine the model._

## At its core, Content-Addressing

The Data Together model builds on an essential technological switch that makes the decentralized web possible. Rather than identifying content by its location, we must use cryptographic hashes to identify content. This is known as content-addressing. Data Together provides a core technical interface —  a progression of “levels” of content-addressed love. Each level unlocks a broader range of possible value-creating activities.

_IMPORTANT: this is just a sketch of what these levels might entail.  The language and characterization of these levels will evolve as Pull Requests against this file. PRs welcome, especially while these documents are in an incomplete "RFC" phase._

**Level 0**: Publish Hashes for the data you hold. If you are an authoritative source for those data, sign the hashes using public key cryptography so that anyone can confirm the authenticity of the data. (examples: gx, ???, docker images?)
**Level 1**: Provide a web-based API that allows people to retrieve content by its hash (github, gitlab, bitbucket, etc)
**Level 2**: The data are available over P2P protocols, meaning peers can use P2P protocols to retrieve content by its hash.
**Level 3**: When you reference data, reference it by Hash.
