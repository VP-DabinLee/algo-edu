# Algorand Education

This repository contains open-source educational content on various aspects of the Algorand network and ecosystem. For information on contribution and how to generated presentations from this content, refer to the [guide](./GUIDE.md)

# en-US Content
| Content | Description | Status | Last Updated | Primary Maintainer |
| ------ | ----------- | ------ | ------------- | ---------- |
| [Network](en-US/network.md) | Overview of Algorand network topology, software, and decentralization | WIP | 09/16/22 | [joe-p](https://github.com/joe-p) |
| [Layer-1 Features](en-US/layer_1.md) | Overview of Algorand's layer-1 performance and features | WIP | 09/16/22 | [joe-p](https://github.com/joe-p) |
| [Smart Contracts](en-US/smart_contracts.md) | Overview of Algorand smart contracts | WIP | 09/16/22 | [joe-p](https://github.com/joe-p) |
| [Development Intro](en-US/dev_intro.md) | Overview of development tools and resources | WIP | 09/16/22  | [joe-p](https://github.com/joe-p) |
| [Intro to PyTeal](en-US/pyteal_intro.md) | Introduction to PyTeal concepts | WIP | 09/16/22 | [joe-p](https://github.com/joe-p) |
| [ASC Security Guidelines](en-US/asc_security.md) | Best practices when building smart contracts on Algorand | WIP | 09/18/22 | [joe-p](https://github.com/joe-p) |
| [Token ARCs](en-US/token_arcs.md) | Overview of token-related ARCs | WIP | 09/18/22 | [joe-p](https://github.com/joe-p) |
| Intro to Beaker | Introduction to JavaScript SDK concepts | TODO | | TBD |
| Intro to JavaScript SDK | Introduction to beaker concepts | TODO | | TBD |
| Governance and Tokenomics | Overview of governance process and tokenomics | TODO | | TBD |
| Community and Ecosystem | Overview of Algorand community and ecosystem | TODO | | TBD |

# en-US Glossary

## A

###### Algorand
A layer-1 blockchain founded in 2017 by cryptography pioneer, Turing award winner and MIT professor Silvio Micali. Offers layer-1 features such as standard assets and smart contracts all while remaining fast, affordable, scalable, and sustainable.

###### Algorand Virtual Machine (AVM)
The execution layer that exists in every algorand node (algod) for executing smart contracts. Algorand's use of the AVM means it is not EVM compatible. 

## P
###### Proof of Stake
A blockchain consensus mechanism that uses the stake to determine probably of an entity in partcipating.

###### Pure Proof of Stake
Three-step consensus mechanism designed by Silvio Micali that leverages VRFs and user-replacability for fast, secure, and scalable consensus on the Algorand network. Any partcipants chance of partcipating in Algorand's consensus is directly proportional to the amount of ALGOs held in their account.

###### State Proof
A relatively small piece of data that can be used to verify the state of the Algorand chain at any given time. State Proofs will play an integral part in multi-chain interopability. 

## V
###### Verifiable Random Function (VRF)
A crpytographic function that can be used to generate random numbers that can also be veried by other parties. VRFs are integral for Algorand's Pure Proof of Stake consensus mechanism. 
