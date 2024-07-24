# Ethereum Smart Contract with React Frontend

## Overview

This repository contains a simple Ethereum smart contract and a React frontend application to interact with it. The contract manages an account balance, allowing the owner to deposit and withdraw funds. The frontend uses MetaMask for user interaction and communicates with the smart contract deployed on the Ethereum blockchain.

## Project Structure

- **`contracts/Assessment.sol`**: The smart contract written in Solidity.
- **`scripts/deploy.js`**: A Hardhat deployment script for deploying the smart contract.
- **`frontend/pages/index.js`**: The main React component for the frontend application.
- **`artifacts/contracts/Assessment.sol/Assessment.json`**: The ABI file for the smart contract.

## Getting Started

### Prerequisites

- Node.js 
- npm 
- MetaMask browser extension
- Hardhat

### Executing program

* Inside the project directory, in the terminal type: ```npm i```
* Open two additional terminals in your VS code
* In the second terminal type: ```npx hardhat node```
* In the third terminal, type: ```npx hardhat run --network localhost scripts/deploy.js```
* Back in the first terminal, type ```npm run dev``` to launch the front-end.
* Install the metamask extension in your web browser
* Add a network manually in your metamask with these fields
  - Name: (can be anything you would like)
  - RPC URL: http://127.0.0.1:8545/
  - Chain ID: 31337
  - Currency Symbol: ETH
* Click save
* Switch to your created network
* Go back to the terminal where you entered ```npx hardhat node``` and copy the private key of Account 0
* Import the account to Metamask

## Authors

Kim Emmanuelle Lalap (kmmrld017@gmail.com)

## License

This project is licensed under the Kim Emmanuelle Lalap License - see the LICENSE.md file for details

