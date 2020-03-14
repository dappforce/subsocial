# Subsocial by [DappForce](https://github.com/dappforce)

Subsocial is an open protocol for decentralized social networks and marketplaces. It's built with Substrate and IPFS.

Features: blogs, posts, comments, upvotes/downvotes, reputation, user feed and notifications, SEO, full-text search.

Try it: [Subsocial.Network](http://subsocial.network/)

## Supported by Web3 Foundation

<img src="./w3f-badge.svg" width="100%" height="200" alt="Web3 Foundation grants badge" />

Subsocial is a recipient of the technical grant from Web3 Foundation. We have successfully delivered all three milestones described in Subsocial's grant application. [Official announcement](https://medium.com/web3foundation/web3-foundation-grants-wave-3-recipients-6426e77f1230).

## Repositories

Subsocial consists of several repositories:

- [Runtime](https://github.com/dappforce/dappforce-subsocial-runtime) - Substrate module. The main blockchain logic of Subsocial is here. It can be used with other Substrate-based blockchains.
- [Node](https://github.com/dappforce/dappforce-subsocial-node) - Substrate-based blockchain node. This repo assembles all Substrate modules required to launch Subsocial as a standalone blockchain.
- [Off-chain storage](https://github.com/dappforce/dappforce-subsocial-offchain) - Saves text data of blogs, posts and comments to IPFS. Builds user feeds and notifications in Postgres. Supports full text search by indexing text data into ElasticSeach database.
- [Web UI](https://github.com/dappforce/dappforce-subsocial-ui) - Mobile friendly web UI for Subsocial blockchain. Built with TypeScript, React, Polkadot API libs and Ant Design components.
- [Docker](https://github.com/dappforce/dappforce-subsocial-starter) - Start all parts of Subsocial in Docker containers with a single script. This will deploy Subsocial blockchain, offchain storage and web UI.

## Demo

[![Subsocial demo #4, 2019-11-28](http://i3.ytimg.com/vi/pFGvlKpJdss/maxresdefault.jpg)](https://www.youtube.com/watch?v=pFGvlKpJdss)

## Mobile friendly

Subsocial features a mobile friendly web UI.

## License

Subsocial is [GPL 3.0](./LICENSE) licensed.
