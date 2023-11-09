# MyToken (META) Solidity Smart Contract

## Overview

This Solidity smart contract, named MyToken (META), provides functionalities for minting and burning tokens on the Ethereum network.

## Contract Details

1. Token Variables:
   - `token_name` (Token Name)
   - `token_abbr` (Token Abbreviation)
   - `total_supply` (Total Token Supply)

2. Balances Mapping:
   - `balances`: Tracks the token balance for each address.

3. Mint Function:
   - `mint(address _address, uint256 _value)`: Increases the total token supply and the balance of the specified address by the given value.

4. Burn Function:
   - `burn(address _address, uint256 _value)`: Reduces the total supply and the balance of the specified address by the given value. Includes conditionals to ensure the sender's balance is sufficient.

## Usage

1. Deployment:
   - Deploy the contract to the Ethereum network.

2. Interacting with the Contract:
   - Use the following functions:
     - `mint(address _address, uint256 _value)`: Mints new tokens.
     - `burn(address _address, uint256 _value)`: Burns tokens.

## License

The contract is licensed under the MIT License.

---

Feel free to deploy and use this contract in accordance with the terms of the MIT License.
