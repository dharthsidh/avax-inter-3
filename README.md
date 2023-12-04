# ERC-20 Token Contract

Welcome to the Ethereum blockchain! This Solidity code represents a basic implementation of an ERC-20 token, a standard interface for fungible tokens on the Ethereum platform. This contract provides the foundation for creating and managing your own digital assets.

## Overview

This ERC-20 token contract includes the following features:

- **Name:** MyToken
- **Symbol:** MYT
- **Decimals:** 18
- **Total Supply:** Defined during contract deployment

## Contract Details

### Functions

1. **Constructor:**
   - Initializes the token with a specified name, symbol, decimals, and initial supply.

2. **Minting Function:**
   - Allows the contract owner to mint new tokens and assign them to a specified address.

3. **Transfer Function:**
   - Enables token transfers from the sender to a specified address.

4. **Approval Function:**
   - Allows the token owner to approve another address to spend tokens on their behalf.

5. **Transfer From Function:**
   - Permits an approved address to transfer tokens from one address to another.

### Owner Management

- The contract includes an owner, and certain functions can only be executed by the owner (`onlyOwner` modifier).

## Getting Started

1. Deploy the contract to the Ethereum blockchain.
2. Interact with the contract using Ethereum-compatible wallets or DApps.

## Usage

- Mint new tokens using the `mint` function.
- Transfer tokens using the `transfer` function.
- Approve spending on your behalf with the `approve` function.
- Transfer tokens from one address to another using the `transferFrom` function.

## Security Considerations

- Ensure the owner address is secure and kept private.
- Review and test thoroughly before deploying to the Ethereum mainnet.

## License

This code is licensed under the MIT License. See the SPDX-License-Identifier comment in the code for details.

# Contact
  Siddharth Boyiri 
