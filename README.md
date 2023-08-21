# Simple ERC-20 Token Contract

This repository contains a simple implementation of an ERC-20 token contract written in Solidity. The ERC-20 token standard is widely used for creating fungible tokens on the Ethereum blockchain.

## Project Overview

This project aims to provide a basic understanding of how ERC-20 tokens work and how to create a simple token contract using Solidity.

The contract in this repository implements the following functionalities:

- Minting new tokens
- Transferring tokens between accounts
- Approving and transferring tokens on behalf of another account

## Getting Started

1. Clone the repository to your local machine using:
```
git clone https://github.com/elio-bteich/erc20-token.git
```

2. Navigate to the project directory:
```
cd erc20-token
```


3. Explore the \`ERC20Token.sol\` file to understand the contract's structure and functions.

4. To deploy and interact with the contract, you can use tools like [Remix](https://remix.ethereum.org/) or [Truffle](https://www.trufflesuite.com/truffle).

## Contract Details

- **Name:** SimpleERC20Token
- **Symbol:** SET
- **Decimals:** 18 (adjustable)
- **Total Supply:** Initially 0 (can be minted by the contract owner)

## Key Functions

- \`totalSupply()\`: Returns the total supply of tokens.
- \`balanceOf(address account)\`: Returns the token balance of a specified account.
- \`mint(uint256 amount)\`: Allows the contract owner to mint new tokens.
- \`transfer(address to, uint256 amount)\`: Allows an account to transfer tokens to another account.
- \`allowance(address owner, address spender)\`: Returns the allowed token amount for a spender.
- \`approve(address spender, uint256 amount)\`: Approves a spender to transfer a specific amount of tokens.
- \`transferFrom(address from, address to, uint256 amount)\`: Allows a spender to transfer tokens on behalf of an owner.

## Security Considerations

- Always be cautious when interacting with smart contracts. Ensure you understand the contract's behavior before sending transactions.
- Follow best practices to prevent common vulnerabilities such as integer overflow/underflow.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

This project was inspired by the desire to learn more about smart contract development and the Ethereum ecosystem.

Feel free to explore, experiment, and build upon this project as you continue your journey into blockchain development! If you have any questions or ideas, please don't hesitate to reach out.

Happy coding! 🚀
