# Voting Dapp
The traditional ways of voting using ballot papers and electoral voting using EVM (Electronic Voting Machine) receive harsh criticism for the little transparency and the high complexity of auditing the votes issued. Adding to this, the distrust of the voters is on the rise, as they are unsure of the integrity, reliability, and anonymity of their identity and the privacy of their votes. This is the reason why it is necessary to find a solution that allows us to gain the mutual trust of the voters and the election candidates.

The Decentralized Application (DApp) is hosted on Web3.0. It is made using ReactJS which is used to design the landing pages of the DApp. React uses a library called Ether.js which helps in the integration and usage of smart contract functions. The DApp interacts with the blockchain (Ethereum network) with the help of the Metamask wallet, which acts as a signer as well as a provider to the decentralized application. 
Ethereum will provide a secure, open-source, and decentralized network. The smart contracts will compile and run on the Ethereum Virtual Machine unique to the blockchain on their own. But on the developer side, Hardhat is used to test, compile, deploy and debug DApps. The DApp will be deployed on the Ropsten Testnetwork for the test run. To ensure anonymity we’ll be using furthermore libraries to ensure privacy and anonymity on the system.

![Architecture  - Research Paper (1)](https://user-images.githubusercontent.com/68750732/206268597-a396aed3-b079-4711-bf91-926b6890f099.png)

## Technology Stack & Tools
- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Web3](https://web3js.readthedocs.io/en/v1.5.2/) (Blockchain Interaction)
- [Truffle](https://www.trufflesuite.com/docs/truffle/overview) (Development Framework)
- [Ganache](https://www.trufflesuite.com/ganache) (For Local Blockchain)

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/), should work with any node version below 16.5.0
- Install [Truffle](https://www.trufflesuite.com/docs/truffle/overview), In your terminal, you can check to see if you have truffle by running `truffle version`. To install truffle run `npm i -g truffle`. Ideal to have truffle version 5.4 to avoid dependency issues.
- Install [Ganache](https://www.trufflesuite.com/ganache).

## Setting Up
### 1. Clone/Download the Repository

### 2. Install Dependencies:
`$ npm install`

### 3. Start Ganache

### 4. Migrate Smart Contracts
`$ truffle migrate --reset`

### 5. Run 1st script
`$ truffle exec .\scripts\1_create_proposal.js`
