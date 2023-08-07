# ETH+AVAX Module 2 Frontend Project

This repository contains my Metacrafters frontend DApp project that interacts with a Solidity smart contract deployed on the local Ethereum network. The DApp allows users to perform deposit and withdraw operations and also includes additional functionalities like calculating factorials and checking palindromes.

## Features

1. **Deposit**: Users can deposit a specified amount into the smart contract.
2. **Withdraw**: Users can withdraw a specified amount from the smart contract.

## Prerequisites

Make sure you have the following tools installed before running the DApp:

- [Node.js](https://nodejs.org) (npm will be installed along with Node.js)
- [MetaMask](https://metamask.io/) browser extension

## Installation

To set up the project, run the following commands in your terminal:

1. Install the required dependencies:

```bash
npm install
```
2. Start a local Ethereum network:

```bash
npx hardhat node
```
3. Deploy the smart contract on the local network:

```bash
npx hardhat run scripts/deploy.js --network localhost
```
## Running the Project
To run the DApp locally, use the following command:

```bash
npm run dev
```
Once the DApp is running, open your browser and navigate to http://localhost:3000 to access the DApp interface.

## How to Use
1. Connect Metamask: Ensure you have the MetaMask extension installed and connected to the local Ethereum network.

2. Wallet Connection: Click the "Please connect your Metamask wallet" button to connect your wallet to the DApp.

3. Deposit: Enter an amount in the input field and click the "Deposit" button to deposit the specified amount into the smart contract.

4. Withdraw: Enter an amount in the input field and click the "Withdraw" button to withdraw the specified amount from the smart contract.

5. Calculate Factorial: Enter a positive number in the input field and click the "Calculate Factorial" button to calculate the factorial of the entered number.

6. Check Palindrome: Enter a number in the input field and click the "Check Palindrome" button to check if the entered number is a palindrome.

7. Display My Info: Click the "Umesh Ola" button to display training and roll number information.

## Owner
Umesh Ola (21BCS10670)
