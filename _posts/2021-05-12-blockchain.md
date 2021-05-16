---
title: What is Blockchain?
tags: [Blockchain]
style: fill
color: primary 
description: Learn about blockchain.
---
Still writing...<br/>
<i> Reference:  </i>

## Overview
Blockchain is one of the most interesting technologies in these days. Bitcoin and Ethereum are the most successful blockchain use case, and other Altcoins (minor coins) are following the major coins. The market size of coins, also known as virtual assets, cryptocurrency, virtual currency, has already excceeded ones of the legacy stock market. There are also fake coins, called SCAM, in the market. To understand why blockchain technology is hot and to avoid SCAM, we should understand the background and go deep into the technology.

## Terminology
- Blockchain
- DLT (Distributed Ledger Technology)
- Genesis block
- Computer Science: Hash, Linked List, SHA 256
- Two general problems
- Byzantine problems
- Consensus algorithm

#### Part 1. Cryptocurrency
### 1. What is Mining?
Mining is a behaivor to gain cryptocurrency as a reward of participating in blockchain network. The kind of participation can be different depending on blockchain: some blockchains, such as Bitcoin, require participators to create blocks of transactions and verify newly created blocks; some blockchain, such as Theta, require participators to share their own memory and bandwidth. In Bitcoin, mining is a behavior to solve hash problems, create blocks of transactions and verify newly created nodes. After solving hash problems and creating a new block, miners gain Bitcoin + commission as a reward. In Theta, mining is a behavior to share memory and bandwidth and verify network. Miners gain TFUEL, gas in Theta network, as a reward. <br/>
The process of mining is as below: <br>
1. Miner installs a mining program listening any requests from blockchain network. 
2. Miner collects transactions in a memory pool until the memory pool is full.
3. When the pool is full, a miner hashes transactions until it reaches to the root of Hash Tree (Merkle Tree). 
4. Root hash, previous block and nounce value is placed on the block header.
5. The block header is hashed with block id, and this hash value must meet the condition (difficulty) defined in the network to meet the balance of number of blocks created and hash rate. In Bitcoin, the difficulty is defined as the hash value starting with N number of 0s. 
6. Miner changes nounce value and find a hash value that meets the current hashcondition.
7. When it finds the solution, miner propagtes the block, and the block is accepted after verifying in other nodes. 
* Here, we can wonder what happened when 2+ valid blocks are propagated to the network. In this case, the first arrived block is accepted in each node, but it can be changed when the next valid block arrives. For example, A node can get A-b and B node can get A-B: both block can be valid. The next block is created with A-B-C, then A node will update its blockchain to A-B-C, and b block is discarded. We call this block as orphan block, stable block.
   
### 1. What is Staking?
Staking is locking cryptocurrency without trading. Cryptocurrency is used not only as a reward but also as a method to maintain security and network in blockchains. Especially, the number of cryptocurrecny is important in blockchains based on PoS (Proof of Stake). In PoS based blockchain, stakeholders who have a large portion of cryptocurrency have a power and responsibility to keep the network secure. For example, in Ethereum 2.0, they have adapted PoS in its blockchain network. (The detailed reasons will be described later.) PoS doesn't require any Proof of Work, such as solving hash problems or others: in other words, rather than finding participants to create blocks in the network by how fast any node solve hash problem, the network finds stakeholders who have a large number of cryptocurreny. Stakeholders with larger portion of cyrptocurrency have a high probability to create blocks.

#### 2. What is Liquid Swap?

<style>
body{
  font-family: 'Roboto', sans-serif;
}
</style>
