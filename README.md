# BlockchainBank

This is a blockchain bank running on Ganache.
Investor stakes mDAI tokens and get rewarded (as interest) with Dapp Tokens whenever owner wants them to. 
* Owner = 1st Ganache account
* Investor = 2nd Ganache account

## Features

* Staking mDAI Tokens
* Earn Dapp Tokens
* Unstaking mDai Tokens 

## Prerequisites

Be sure you have the following installed on your development machine:

+ node.js
+ Ganache
+ Truffle = v.5.1.39
+ MetaMask Chrome extension

## Project Installation

To setup a local development environment:

### Install development dependencies,
Install Node.js from https://nodejs.org/en/ and Ganache from https://www.trufflesuite.com/ganache
and truffle through-
```bash
npm install --g truffle@5.1.39
```
Set up MetaMask extension for second Account of Ganache


### Clone GitHub Project,
```bash
git clone https://github.com/siDcover/Blockchain-Bank Blockchain_Bank
```

### Migrate and Deploy,
```bash
truffle migrate
```
or,
```bash
truffle migrate --reset
```

### Run the web application locally,
```bash
npm run start
```

### Issue Dapp Tokens for staking,
```bash
truffle exec scripts/issue-tokens.js
```
