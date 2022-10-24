# Blockchain

> A blockchain is a **shared**, **distributed**, and **permanent** **database** shared among multiple nodes on a computer network. They record data in a way that makes it probabilistically **impossible to modify** or hack the system.

## Stage Management

Blockchains record data as **a chain of blocks**, each block contains a group of **transactions**.

![](https://i.imgur.com/VQySjQu.png)

A **genesis block** is the first block of a block chain. 

![](https://i.imgur.com/wjK9Foy.png)

These blocks are chained together in a **cryptographically verifiable way** so they are **historically traceable**. The current state of a network **can be recalculated at any time** by starting from the genesis block and transitioning the state according to each block's information up until now.

## Nodes

Each node in the network as **keeping a copy of the global transaction ledger**.

Each node **can individually verify and audit transactions** happening on the network and **ensure there was no illicit behaviour.**

**<u>Mining node</u>** is responsible for **grouping together new transactions being made on a network into a block**, verifying them, and proposing the block to be included onto the global ledger by everyone else.

## Decentralization

- **Traditional**: Storing data in a centralized manner.

- **Blockchain**: Storing data in a peer to peer (P2P) network of nodes.

  - **No censorship** as there is no single authority or middleman that can censor you

  - **No downtime** as the overall network is running across 1000's of nodes across the globe

  - **Highly attack resistant** making it infeasible to manipulate or destroy data

> [Blockchain Demo](https://andersbrownworth.com/blockchain/)