# A Concise Introduction to Data Together

## The Ethos

The essential ethos behind Data Together:

If I rely on data, I should be able to hold copies of the data. If I don’t personally have the resources to hold the copies, I should be able to coordinate with the people around me to hold the data as collective assets. This activity, where people and communities replicate the data they rely on, should reinforce access, discovery and preservation of the data; this activity should make the network of connections more dense rather than making it sparse/scattered. Likewise, if I create data I should be able to apply these same principles.

This ethos lies at the core of the mission to build a decentralized web. Peer to peer technologies make the vision possible. Data Together provides a model for Institutions, Community Organizations, Government Agencies and NGOs to support these activities and use them to fulfill their missions.

## The Model

The Data Together model builds on an essential technological switch that makes the decentralized web possible. Rather than identifying content by its location, we must use cryptographic hashes to identify content. This is known as content-addressing. Data Together provides a core technical interface —  a progression of “levels” of content-addressed love. Each level unlocks a broader range of possible value-creating activities.

_IMPORTANT: this is just a sketch of what these levels might entail. The actual model will evolve as Pull Requests against the [datatogether github repository](https://github.com/datatogether/datatogether/), especially focusing on the [about/model directory](./model/README.md)_

**Level 0**: Publish Hashes for the data you hold. If you are an authoritative source for those data, sign the hashes using public key cryptography so that anyone can confirm the authenticity of the data. (examples: gx, ???, docker images?)
**Level 1**: Provide a web-based API that allows people to retrieve content by its hash (github, gitlab, bitbucket, etc)
**Level 2**: The data are available over P2P protocols, meaning peers can use P2P protocols to retrieve content by its hash.
**Level 3**: When you reference data, reference it by Hash.
