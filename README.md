# ERC20Mod3Proj Contract

This is a basic ERC-20 token contract written in Solidity. It allows for the creation, transfer, and management of a custom token called "EbokCoin" (EBC).

## Features

* Token Creation: The contract creates a total supply of 1000 EBC tokens, with 18 decimal places.
* Token Management: The contract allows the owner to mint new tokens, burn existing tokens, and transfer tokens to other addresses.
* Transfer: Users can transfer tokens to other addresses.
* Events: The contract emits events for token transfers, mints, and burns.

## Functions

### Constructor

* Initializes the contract with the token name, symbol, decimals, and total supply.
* Sets the owner of the contract to the deployer.
* Mints tokens to a list of predefined addresses.

### mint

* Allows the owner to mint new tokens to a specified address.
* Emits a `Mint` event.

### burn

* Allows users to burn tokens from their balance.
* Emits a `Transfer` event.

### transfer

* Allows users to transfer tokens to other addresses.
* Emits a `Transfer` event.

## Security

* The contract uses a `onlyOwner` modifier to restrict certain functions to the contract owner.
* The contract uses `require` statements to validate input parameters and prevent unauthorized actions.

## Deployment

To deploy this contract, simply compile and deploy it to a compatible Ethereum network using your preferred development environment.

## Testing

To test this contract, you can use a testing framework such as Truffle or Hardhat to write and execute test cases.

## License

This contract is licensed under the MIT License.

## Contract Address

TBD (update with the deployed contract address)

## Token Details

* **Name**: EbokCoin
* **Symbol**: EBC
* **Decimals**: 18
* **Total Supply**: 1000 EBC

## Authors

[Your Name]

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## Issues

If you encounter any issues with this contract, please open an issue in this repository.
