# ETH+AVAX Intermediate Assessment - 3

A simple ERC-20 token named "PikuCoin" with the symbol "PC". This smart contract allows the contract owner to mint tokens, while any user can transfer and burn tokens.

## Description

The MyToken project implements a basic ERC-20 token using OpenZeppelin libraries. The contract includes functionality for minting, transferring, and burning tokens:
- Only the contract owner can mint new tokens.
- Any user can transfer tokens to another address.
- Any user can burn their own tokens.

## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. Follow these steps:

1. **Open Remix IDE**: Visit [Remix IDE](https://remix.ethereum.org/).
2. **Create a New File**: Click on the "+" icon in the left-hand sidebar. Save the file with a `.sol` extension (e.g., `MyToken.sol`).
3. **Copy the Code**: Copy and paste the code from the [ETH+AVAX-Intermediate-Assessment-3.sol](ETH+AVAX-Intermediate-Assessment-3.sol) file into your new file in Remix.
4. **Compile the Code**: Click on the "Solidity Compiler" tab in the left-hand sidebar. Ensure the "Compiler" version is set to `0.8.20` or higher. Then click the "Compile MyToken.sol" button.
5. **Deploy the Contract**: Go to the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyToken" contract from the dropdown menu and click the "Deploy" button.

### Interact with the Contract

- **Mint Tokens**: As the contract owner, use the `mint` function to create new tokens. Provide the recipient address and the amount of tokens to mint.
- **Transfer Tokens**: Any user can transfer tokens by calling the `transfer` function with the recipient address and the amount of tokens.
- **Burn Tokens**: Any user can burn tokens by calling the `burn` function with the amount of tokens to burn.

### Modifications

No modifications are required for basic functionality. If you wish to expand the contract's capabilities or customize its behavior, you can modify the code accordingly.

## Authors

Parteek Batheja  
[@ParteekBatheja](https://github.com/ParteekBatheja)

## License

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.
