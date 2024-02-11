# degenToken Smart Contract

## Overview

This repository contains the source code for the `degenToken` smart contract, which is an ERC20-compliant token deployed on the Ethereum blockchain. This token is named "degenToken" with the symbol "DT". The contract inherits functionalities from the OpenZeppelin ERC20, Ownable, and ERC20Burnable implementations.

## Features

The `degenToken` contract provides the following features:

1. **Token Initialization**: Upon deployment, the contract creator becomes the initial owner of the token.

2. **Mint Tokens**: The contract owner can mint additional tokens for a specified address using the `mintTokens` function.

3. **Burn Tokens**: Token holders can burn a specified amount of their tokens using the `burnTokens` function.

4. **Redeem Lipstick**: Token holders can redeem lipstick using their tokens. Available lipstick types are "Glossy_Lipstick" and "Matte_Lipstick", each with a corresponding price in tokens.

5. **Transfer Tokens**: Token holders can transfer tokens to another address using the `transferTokens` function.

## Usage

To use this contract, deploy it to an Ethereum-compatible blockchain network. After deployment:

- You can interact with the contract using any Ethereum wallet or by calling its functions from another smart contract.
- The contract owner can mint additional tokens and transfer ownership as needed.
- Token holders can burn tokens, redeem lipstick, and transfer tokens to other addresses.

## Author

Pushpa

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

