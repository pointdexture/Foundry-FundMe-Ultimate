# About

The Blockchain FundMe App is a decentralized crowdfunding platform built on blockchain technology. It allows users to create and contribute to fundraising campaigns for various projects, leveraging the transparency, security, and immutability of the blockchain.

# Features

Transparent Progress Tracking: The campaign's funding progress, transactions, and updates are recorded on the blockchain, providing transparent and immutable tracking.

Automatic Payouts: Once a campaign reaches its funding goal within the specified duration, the smart contract automatically initiates the payout to the campaign creator's wallet.

Anti-Fraud Measures: Smart contracts are designed to prevent fraudulent activities and false claims during the campaign.

## Requirements

## Contribution

Contributions to the Blockchain Fund Me App are welcome! As blockchain development can be complex, your expertise in auditing smart contracts, optimizing gas fees, or enhancing security will be highly valuable.

## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

- **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
- **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
- **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
- **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
