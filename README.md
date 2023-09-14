

# MyToken - Custom ERC-20 Token Contract

## Introduction

This repository contains a custom Ethereum ERC-20 token contract called "MyToken." The contract is implemented in Solidity and includes the ability to mint tokens for the contract owner and allows users to burn and transfer tokens. It serves as a basic example of an ERC-20 token with additional functionalities.

## Contract Details

- **Name**: BENCH (BNH)
- **Symbol**: BNH
- **Decimals**: 18
- **Initial Supply**: 1,000,000 tokens (1 million tokens with 18 decimals) minted to the contract owner upon deployment.

## Contract Functions

1. **Mint Tokens**: The contract owner can mint additional tokens to a specified address using the `mint` function.

2. **Burn Tokens**: Any user can burn their own tokens using the `burn` function.

3. **Transfer Tokens**: Users can transfer tokens between addresses using the standard ERC-20 `transfer` function.

4. **Check Balances**: Users can check the token balance of any address using the standard ERC-20 `balanceOf` function.

## Getting Started

To deploy and interact with the MyToken contract, follow these steps:

1. **Deployment**:
   
   - Deploy the contract using Remix (https://remix.ethereum.org/).

2. **Mint Tokens**:

   - Use the `mint` function to create new tokens and assign them to a specified address. This function can only be called by the contract owner.

3. **Burn Tokens**:

   - Use the `burn` function to destroy tokens from your own address. This function is available to all users.

4. **Transfer Tokens**:

   - Use the standard ERC-20 `transfer` function to send tokens from your address to another address.

5. **Check Balances**:

   - Use the standard ERC-20 `balanceOf` function to check the token balance of any address.

## Security Considerations

This contract is provided for educational purposes and may not be suitable for production use without additional security measures. Ensure that proper access control and security mechanisms are implemented as needed for your specific use case.

## License

This contract is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for details.
