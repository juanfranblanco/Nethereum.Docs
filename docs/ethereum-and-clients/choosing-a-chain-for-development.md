# Choosing a chain for your development environment 

When developing on Ethereum, different approaches are required depending on your development environment. Below are some tools we recommend:

## Local private testnet

There are many ways to setup a tesnet locally, and different types of consensus to chose from. Currently the best way to work locally is to use ``` Geth using Proof of Authority "Clique" ```, ``` Parity Proof of Authority ``` and / or ``` Ganache CLI  (Old TestRpc)```

### Geth Proof of Authority (Clique)

Geth Clique allows you to test your integration with smart contracts directly in the Golang client Geth with a fast Proof of Authority consensus. The preconfigured single node we provide, provides near instant response with all the features of Geth.

[Geth Clique Manual](geth.md)

### Parity Proof of Authority

Similar to Geth Clique, Parity Proof of Authority allows you to test your integration with smart contracts directly in the Rust client Parity with a fast Proof of Authority consensus. This is also preconfigured as a single node with near instant and all the features of Parity.

[Parity Clique Manual](parity.md)

### Ganache-CLI

``` Ganache CLI ``` (formerly ``` Test RPC ```) is a chain simulator part of the Truffle suite. The Truffle suite provides the development tools for Smart Contract unit testing, debugging and deployment.

[Ganache official repo](https://github.com/trufflesuite/ganache-cli)

## Cloud private testnet

The Azure BaaS (Blockchain as a Service) allows you to deploy a testnet with several nodes and a generic team working environment.
THIS NEED TO POINT TO OUR GUIDE OF HOW TO USE THE AZURE BAAS
[Azure BaaS Documentation](https://azure.microsoft.com/en-us/solutions/blockchain/) 

## Public testnets

Public testnets function in the same way main nets work, with two differences:
* They are free: transactions are paid with a worthless crypto-currency
* They are often more responsive than main nets 

The main public testchains are:

#### 1. Rinkeby

Cross-client testnet using PoA consensus mechanism.

[Rinkeby Official Site](https://www.rinkeby.io)

#### 2. Kovan

Cross-client testnet (working with both Parity and Geth) using PoA consensus mechanism and a particular focus on spam-resilience.  

[Kovan Official Site](https://kovan-testnet.github.io/website/)

#### 3. Ropsten

Less popular now, Ropsten is still in service.

[Ropsten Github Repo](https://github.com/ethereum/ropsten)

NOTE JUAN: This needs to link to our Infura document
Note: public testnets can be accessed via public nodes such as [INFURA](https://www.infura.io) 

For more info on public testnets check Karl Floersch [blog post](https://karl.tech/intro-guide-to-ethereum-testnets/)

## Ether Faucets

The ether and tokens used in test networks is for testing purposes only (it can accurately be compared to Monopoly bills). It's mostly distributed by online "faucets". 

Here's a list of testnet Ether sources:

| Testnet Name | Faucet|
|----------------------|-------|
|Rinkeby| https://www.rinkeby.io/#faucet|
|Ropsten|https://blog.b9lab.com/when-we-first-built-our-faucet-we-deployed-it-on-the-morden-testnet-70bfbf4e317e|
| Kovan | Kovan requires you to request KETH from another person|

TODO Metamask faucet

## Setting up your own Faucet
If you require to setup your own Faucet for your testnet using Nethereum chek the [Nethereum.Faucet](https://github.com/Nethereum/Nethereum.Faucet) further explained in [this blog post](https://medium.com/@juanfranblanco/netherum-faucet-and-nuget-templates-4a088f06933d)

