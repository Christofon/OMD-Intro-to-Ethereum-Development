# Get started with Ethereum Development
## Module 1 - General Overview
### What is Blockchain
Basic introduction what Blockchain is, where it comes from and a rough outline how it works.

* intro to the economics side
	* what is money today
	* money in the past
	* bottlenecks in current system
	* what money could/should be
* Consensus mechanism
	* byzantine problem
* decentralization
* Use cases
* Current state of technology i.e. PoW
* Bitcoin

### Ethereum 
* How does it differ (i.e EVM)
* running nodes
* Smart Contracts
	* Dapps 
	* Solidity/Vyper
	* Tokens
* Possible use cases / showcasing dapps
* What is it now vs what it aims to be in the future
	* Outline current problems in the field
	* PoS

**Bounty:** ?

## Module 2 - Using Ethereum
Showcasing existing dapps and interacting with them. Sending transaction/calling functions. 

* testnet vs mainnet 
	* faucets
* gas cost
* chain explorers
* units
* public/private keys
* mnemonic phrase
* general measures to safely use the network
	* key security
	* hot/cold storage
* gotchas in comparison to traditional client-server architecture
	* confirmation times
	* state changes/computing in the EVM vs retrieving data
	* emphasising on cost of computation (eg. Iterating over data)

**Bounty:** Setting up a wallet with metamask and send transactions on testnet to each other / interacting with contract

## Module 3 - Intro to Smart Contracts
Brief intro to contract development, testing and deployment. Different tools intro

* Intro to smart contract first with remix and JS VM
	* following [Solidity by Example — Solidity 0.6.1 documentation](https://solidity.readthedocs.io/en/v0.6.1/solidity-by-example.html) 
	* **or** writing a basic contract together 
* transition to IDE and CLI
* testing the contract  with ganache
* compiling SC and deploying it on testnet
*  tools
	* web3.js
	* truffle/waffle (maybe not using them for the sake of clarity)
	* testnets/ganache
	* infura
* linking basic front end (eg. react) 

**Bounty:** deploying a contract and make it possible to interact with it conveniently

## Module 4 - SC Deep Dive
**TBD**