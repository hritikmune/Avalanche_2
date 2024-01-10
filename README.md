# 2nd Module project For Avalanche 

This is a Solidity smart contract for managing an account with deposit ,burn and withdrawal functionality.

## Description

The Assessment smart contract allows for basic account management, enabling deposits, burn and withdrawals. It logs transactions and provides an overview of the transaction history.


## Requirements 
. Etherium development environment
.Visual Studio 
. Node Js



## Functions of code 

'constructor(uint256 initBalance) payable'
Initializes the contract with an initial balance.

'getBalance() public view returns (uint256)'
Retrieves the current balance of the account.

'deposit(uint256 _amount) public payable'
Allows the owner to deposit funds into the account.

'withdraw(uint256 _withdrawAmount) public'
Allows the owner to withdraw funds from the account.

'getTransactionHistory() public view returns (Transaction[] memory)'
Retrieves the transaction history.

'addressToString(address _addr) internal pure returns (string memory)'
Utility function to convert an address to a string.

## Author 
Hritik Mune
