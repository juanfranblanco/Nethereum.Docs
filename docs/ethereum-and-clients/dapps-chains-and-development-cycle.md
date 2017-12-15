# Dapps, chains and development cycle

## Local private tesnet
When working in your local development environment, some of the options that we have chosen are the following, Geth Clique, Parity PoA and Ganache CLI. 

### Geth
Using Geth Clique you can test directly in Geth your integration with smart contracs in a fast Proof of Authority consensus.
Link to the document.

### Parity
Using POA fast

### Ganache-CLI
If you are working on smart contracts,
Truffle, test rpc replacement, all the beauty of truffle suite, testing smmart contracts, debugging etc.

(We need a section for debugging, on parity, geth, and ganache it is much easier)

## Cloud private testnet
Azure BaaS, Blockchain as a Service, by using the Azure BaaS you can deploy a tesnet with several nodes, which the whole development team can collaborate. Link to document to setup

### Public testnets
Some general info on public testnets, and a link to the infura doc, but in the infura doc where possible some info on faucets.

### Main net


It is common practice to use different Ethereum-based blockchains (or emulators) along the development of a Dapp.

The following is meant to be a quick intro on what Blockchains to use along the development cycle.

### 1 - Dapp at development stage

- [Test RPC/Ganache](https://github.com/trufflesuite/ganache-cli)
Test RPC is not a Blockchaink but a Blockchain simulator. With a quasi-immediate response time and great feedback cycle.
It's ideal to deploy contracts and interact with them instantly at no GAS cost.


### 2 - Dapp at testing stage

Once a Dapp is functional enough to deploy on an actual blockchain but not robust/secure enough to be exposed to the Main Net, you might want to opt for "Public Testnets". Testnets are real blockchains, with an immutable ledger and a consensus system, but their currency has no value, making transactions on their network totally free.


The main public testchains are:

##### 1. Ropsten

Less popular since hacked early 2017, however, it's still fully functional.


##### 2. Rinkeby
Any comments on it Juan?

##### 3. Kovan

Any comments on it Juan?

**Note:** Where do I find Ether to use a testnet?...

The ether and tokens on test networks is generally worthless and is used for testing purposes only. It's often distributed in "faucets". Faucets are best found by using keywords such as  testnet's name (```Rinkeby, Ropsten, Kovan```) + ```faucet```. We chose not to provide URLs as they change all the time :)
You can read Nethereum-specific advice about faucets [here](https://medium.com/@juanfranblanco/netherum-faucet-and-nuget-templates-4a088f06933d)

### 3 - Dapp at deployment stage

Once your Dapp is ready for deployment, it is time to release it on the Mainnet.

Any comments on it Juan?



**Credits**  to [Karl Floersch](https://karl.tech) for the technical part of this explanation: https://karl.tech/intro-guide-to-ethereum-testnets/
