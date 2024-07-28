# PayPool Smart Contract

## Introduction

This is a simple PayPool smart contract with enhanced functionality for storing and managing deposits using structs and enums.

## Contract Details

### Structs

- **DepositRecord**: Stores information about each deposit (depositor, amount, timestamp, status).

### Enums

- **DepositStatus**: Represents the status of a deposit (Pending, Approved, Rejected).

### Functions

- `addDepositAddress(address depositor)`: Adds an address allowed to deposit.
- `deposit()`: Allows allowed addresses to deposit ether.
- `approveDeposit(uint256 index)`: Approves a pending deposit.
- `rejectDeposit(uint256 index)`: Rejects a pending deposit.
- `getDepositHistory()`: Returns the history of deposits.

## Deployment

The contract is deployed on the Scroll Sepolia testnet.

## Interactions

Use the deployed contract interface on Remix or through a script to interact with the functions.

## License

MIT
