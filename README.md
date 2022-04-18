# web3-tech-stack
The open web3 tech stack summarized in one repository. The tools you need to know about in order to build dapps. Curated by the community. 

# The Web3 Abstraction Layers 
1) Nodes
2) APIs
3) Platforms
4) SDKs

## Nodes

All blockchains are essentially networks of servers speaking to each other and sharing the state of the ledger and all smart contracts. 
These servers are called nodes. Nodes run a special piece of software which allows the server to participate in the network. An example of such ofware can be `geth`.

By running `geth` you can get the most basic blockchain information such as the current block, previous blocks, get information about transactions and interact with smart contracts. You interact with `geth` via the RPC protocol.

### RPC Node Providers

You can run `geth` yourself - but you will most likely use one of the node top providers:
1) [Moralis](https://moralis.io)
2) [Chainstack](https://chainstack.com/)
3) [Infura](https://infura.io/)
4) [Alchemy](https://www.alchemy.com/)
5) [GetBlock](https://getblock.io/) 

### The Problem with Nodes

The problem with nodes is that they unfortunately can't give you a lot of meaningful information such as all tokens of a user, all NFTs of a user, volume in a decentralized exchange etc.

This makes the nodes practically use-less for the average dapp developer as you are required to run a backend infrastructure to pull out the low-level information and make sense of it. This process of making sense of node data by processing it on the backend is called `indexing`.

Instead of doing all this heavy-lifting yourself you will most likely use an API.

## APIs
