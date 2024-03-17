# InitialCoinOffering(ICO)--SmartContract

ERC-20 tokens
==============
The ERC-20 (Ethereum Request-for-Comments #20) Token Standard allows for fungible tokens on the Ethereum blockchain. The standard, proposed by Fabian Vogelsteller in November 2015, implements an API for tokens within smart contracts. The standard provides functions that include the transfer of tokens from one account to another, getting the current token balance of an account, and getting the total supply of the token available on the network. Smart contracts that correctly implement ERC-20 processes are called ERC-20 Token Contracts, and they keep track of created tokens on Ethereum. Numerous cryptocurrencies have launched as ERC-20 tokens and have been distributed through initial coin offerings.


Getting Started
===============
**Try running the below commands :**

truffle init

npm install @truffle/hdwallet-provider

truffle console --network sepolia //javascript interactive console to interact with smart contract connected to goerli

**Create a JavaScript migration script,**

01-CryptosICO-deployment.js

**Add sepolia network in truffle-config.js file,**

**Deploy on sepolia networkID 11155111 through Infura API key**

truffle migrate --network sepolia

