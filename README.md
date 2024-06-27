# ERC20 Token Contract
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This repository contains a smart contract implementation of an ERC20 token, which is a standard for fungible tokens on the Ethereum blockchain. The contract provides a basic functionality for creating, managing, and transferring tokens.
Features

### Features :

- Follows the ERC20 token standard
- Supports token creation with a fixed total supply
- Allows token transfers between addresses
- Includes basic access control mechanisms
- Provides events for tracking token transfers and approvals

### Usage : 

- `name()` : Returns the name of the token
- `symbol()`: Returns the symbol of the token
- `decimals()`: Returns the number of decimals the token uses
- `totalSupply()`: Returns the total token supply
- `balanceOf(address account)`: Returns the amount of tokens owned by the specified address
- `transfer(address recipient, uint256 amount)`: Transfers tokens to the specified address
- `approve(address spender, uint256 amount)`: Allows the specified address to spend tokens on behalf of the caller
- `allowance(address owner, address spender)`: Returns the remaining number of tokens that the spender will be allowed to spend on behalf of owner
- `transferFrom(address sender, address recipient, uint256 amount)`: Transfers tokens from one address to another


