# Donation Pool Contract

This smart contract allows users to donate funds to a pool, and the owner of the contract can withdraw the funds. The contract tracks individual donations and the total amount of donations.

## Features

- Users can donate any amount of ETH to the pool.
- The owner can withdraw funds from the pool.
- The contract keeps track of individual and total donations.

## How to Use

1. Deploy the contract on a Solidity-compatible blockchain.
2. Use the `donate()` function to contribute to the donation pool.
3. The owner can use the `withdraw()` function to withdraw funds from the pool.
4. Use the `getContractBalance()` function to view the current balance of the contract.

## Security Considerations

- Ensure that the contract owner is trustworthy, as they have the authority to withdraw funds.
- This contract does not have a mechanism to return donations; once funds are donated, they can only be withdrawn by the owner.
