# MyToken - ERC20 Token

## Overview
**MyToken** is an ERC20 token implemented in Solidity, allowing users to mint, transfer, and burn tokens. This project demonstrates the creation of a simple ERC20 token using the OpenZeppelin library in the Remix IDE.

## Features
- **Minting**: The contract mints an initial supply of tokens to the deployer's address.
- **Token Transfer**: Users can transfer tokens to other addresses.
- **Token Burn**: Users can burn their tokens to reduce the total supply.

## Contract Details
- **Token Name**: bitcoin
- **Token Symbol**: BTC
- **Initial Supply**: 10,000 BTC minted to the deployer's address.


## Technologies Used
- **Solidity**: Programming language for smart contracts.
- **OpenZeppelin**: Library for secure smart contract development.
- **Remix IDE**: Online IDE for Solidity development.

## Getting Started

### Prerequisites
- An Ethereum wallet (e.g., MetaMask) if deploying on a live network.
- A browser to access Remix IDE: [Remix Ethereum IDE](https://remix.ethereum.org/).

### Deployment Steps
1. **Open Remix**: Go to [Remix IDE](https://remix.ethereum.org/).
2. **Create a New File**: Create a file named `MyToken.sol`.
3. **Paste the Contract Code**: Copy the provided ERC20 token contract code into the file.
4. **Compile the Contract**: Use the Solidity Compiler tab to compile the contract.
5. **Deploy the Contract**:
   - Set the environment to **Remix VM (London)**.
   - Choose any of the default accounts for deployment.
   - Click **Deploy**.
6. **Interact with the Contract**: Use the provided functions to check balances, transfer tokens, and burn tokens.

## Contract Functions
- **constructor**: Mints an initial supply of tokens to the deployer's address.
- **tokenTransfer(address recipient, uint256 amount)**: Transfers a specified amount of tokens to the recipient address.
- **tokenBurn(uint256 amount)**: Burns a specified amount of tokens from the caller's balance.

## License
This project is licensed under the MIT License.

## Author
Gagan Chaudhary
