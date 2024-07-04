MyWallet Smart Contract

MyWallet is a Solidity smart contract designed to manage a wallet with specific features such as owner allowances, guardian-based ownership transfer, and transaction control.
Features

    Owner Management: The contract owner can set allowances and permissions for other addresses to send transactions.
    Guardianship: Guardians can propose a new owner, and upon reaching a consensus, the ownership can be transferred.
    Transaction Control: Only the owner or allowed addresses can execute transactions, and each transaction must not exceed the predefined allowance.

Usage

    Deploy the Contract: Deploy the contract on a suitable Ethereum network using your preferred deployment tool.
    Set Allowances: As the owner, use the setAllowance function to specify how much each address can send.
    Propose New Owner: Guardians can propose a new owner using the proposeNewOwner function. Once the required number of guardians confirm, the ownership will be transferred.
    Send Transactions: Allowed addresses can send transactions within their allowance using the transfer function.
