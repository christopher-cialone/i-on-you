## *I On You Review & Reputation System*
### *Designed | Developed | Deployed by Christopher Cialone for Rosalone Labs*
### *Full Dev Docs found on GitBook https://app.gitbook.com/o/1UVoCAqd0OTeffxOKntk/s/e4B1IFyCAD4BpSM9EjCt/requirements*

#### The I On You Review reputation system is a decentralized application (dApp) designed to empower users by providing detailed and specific industry-related information about businesses, enabling them to align with companies that share their values. By leveraging blockchain technology, Chainlink services, and IPFS, the system ensures transparency, reliability, and security. Businesses that actively address user feedback are rewarded with tokenized incentives, fostering a responsive and accountable business environment.

- **Objectives**
- **Empower users with accurate and comprehensive information about businesses**
- **Encourage businesses to respond to user feedback by providing tokenized incentives**
- **Ensure data transparency and integrity using blockchain and IPFS**
- **Facilitate seamless integration with other Web3 applications via APIs**

## Requirements
- **Must Have:**
- **Ability for users to query businesses using an API that triggers ChatGPT to gather information about the business’s values, missions, and political donations**
- **Storage of data on IPFS, with pinning managed through Pinata to ensure data availability**
- **Tokenized incentives for businesses that address user concerns, visible in marketing spaces on affiliate apps**
- **User reviews and feedback mechanism directly on the platform**
- **Integration with Avalanche blockchain for decentralized operations**
- **Use of Chainlink for secure external data fetching and verification using VRF (Verifiable Random Function)**
- **Creation of state change on the blockchain**
  
## *Compiled | Tested | Deployed using Foundry*

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

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
# i-on-you
