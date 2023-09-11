# awesome-ethereum-rust
Awesome Ethereum Rust repos

- [Consensus](#consensus)
- [Execution](#execution)
- [EVM - Ethereum Virtual Machine](#evm---ethereum-virtual-machine)
- [Core](#core)
- [Light Clients](#light-clients)
- [Scaling](#scaling)
- [PBS - Proposer-Builder Separation](#pbs---proposer-builder-separation)
- [Account Abstraction](#account-abstraction)
- [zkEVM](#zkevm)
- [Statelessness](#statelessness)
- [Layer 2](#layer-2)
- [dApp Development](#dapp-development)
- [Smart Contracts](#smart-contracts)
- [Data Analytics](#data-analytics)

## Consensus

- [Lighthouse](https://github.com/sigp/lighthouse).
Ethereum consensus client.
- [ethereum-consensus](https://github.com/ralexstokes/ethereum-consensus).
A library for interacting with Ethereum consensus objects.
- [beacon-api-client](https://github.com/ralexstokes/beacon-api-client).
A client for the Ethereum beacon node APIs.
- [discv5](https://github.com/sigp/discv5).
Rust implementation of Discovery v5.

## Execution

- [Reth](https://github.com/paradigmxyz/reth).
Ethereum execution client.

## EVM - Ethereum Virtual Machine

- [Revm](https://github.com/bluealloy/revm/).
Rust Ethereum virtual machine (revm) Is EVM written in rust that is focused on speed and simplicity.

## Core

- [Alloy](https://github.com/alloy-rs/core).
High-performance, well-tested & documented core libraries for Ethereum.
- [ethers-rs](https://github.com/gakonst/ethers-rs/).
Complete Ethereum library and wallet implementation.
- [Reth](https://github.com/paradigmxyz/reth).
Modular, contributor-friendly and blazing-fast implementation of the Ethereum protocol.
- [ssz-rs](https://github.com/ralexstokes/ssz-rs).
Implementation of Ethereum's ssz.

## Light Clients

- [Trin](https://github.com/ethereum/trin).
An Ethereum portal client: a json-rpc server with nearly instant sync, and low CPU & storage usage.
- [Helios](https://github.com/a16z/helios).
A fast, secure, and portable light client for Ethereum.

## Scaling

- [proto-danksharding-crypto](https://github.com/crate-crypto/proto-danksharding-crypto).
Proto-Danksharding Cryptography.
- [c-kzg-4844](https://github.com/ethereum/c-kzg-4844/blob/main/bindings/rust/README.md).
Minimal 4844 version of c-kzg (bindings for Rust).
- [KZG Ceremony Sequencer](https://github.com/ethereum/kzg-ceremony-sequencer).
This implements KZG Ceremony Specification.

## PBS - Proposer-Builder Separation

- [mev-rs](https://github.com/ralexstokes/mev-rs/).
A gateway to a network of block builders.
- [evangelion](https://github.com/jacobkaufmann/evangelion/).
A prototype Ethereum block builder.
- [ethers-flashbots](https://github.com/onbjerg/ethers-flashbots).
An Ethers middleware for submitting Flashbots bundles.
- [Artemis](https://github.com/paradigmxyz/artemis).
A simple, modular, and fast framework for writing MEV bots.
- [mev-share-rs](https://github.com/paradigmxyz/mev-share-rs).
Rust client library for Flashbots MEV-share.

## Account Abstraction

- [Silius](https://github.com/Vid201/silius/).
ERC-4337 (Account Abstraction) - modular and efficient bundler implementation.
- [ethers-userop](https://github.com/qi-protocol/ethers-userop/).
An ether-rs middleware to craft user operations.
- [UoIndexer](https://github.com/zsluedem/UoIndexer).
User operation indexer for ERC-4337.

## zkEVM

- [Zeth](https://github.com/risc0/zeth).
A "Type 0" zkEVM. Prove validity of Ethereum blocks using RISC Zero's zkVM.

## Statelessness

- [rust-verkle](https://github.com/crate-crypto/rust-verkle).
This is a proof of concept implementation of Verkle Tries.

## Layer 2

### Arbitrum
- [Stylus](https://github.com/OffchainLabs/stylus-sdk-rs).
Rust Smart Contracts on Arbitrum.

### Optimism
- [op-reth](https://github.com/anton-rs/op-reth).
Optimism + Reth.
- [Magi](https://github.com/a16z/magi).
A blazing fast OP Stack rollup client.

### StarkNet
- [StarkNet Foundry](https://github.com/foundry-rs/starknet-foundry).
Blazing fast toolkit for developing Starknet contracts.
- [Madara](https://github.com/keep-starknet-strange/madara).
Madara is a blazing fast Starknet sequencer, based on substrate.
- [Papyrus](https://github.com/starkware-libs/papyrus).
Papyrus is a StarkNet full node written.
- [starknet-rs](https://github.com/xJonathanLEI/starknet-rs).
Complete Starknet library.
- [Cairo](https://github.com/starkware-libs/cairo).
Cairo is the first Turing-complete language for creating provable programs for general computation.

### ZkSync
- [zksync-era](https://github.com/matter-labs/zksync-era).
zkSync era.

## dApp Development

- [Foundry](https://github.com/foundry-rs/foundry).
Foundry is a blazing fast, portable and modular toolkit for Ethereum application development.
- [Rivet](https://github.com/paradigmxyz/rivet).
Developer Wallet & DevTools for Anvil.

## Smart Contracts

- [Heimdall](https://github.com/Jon-Becker/heimdall-rs).
Heimdall is an advanced EVM smart contract toolkit specializing in bytecode analysis.
- [ethabi](https://github.com/rust-ethereum/ethabi).
Encode and decode smart contract invocations.
- [Pyrometer](https://github.com/nascentxyz/pyrometer).
A tool for analyzing the security and parameters of a solidity smart contract.
- [Fe](https://github.com/ethereum/fe).
Emerging smart contract language for the Ethereum blockchain.
- [svm-rs](https://github.com/alloy-rs/svm-rs).
Solidity-Compiler Version Manager.

## Data Analytics

- [cryo](https://github.com/paradigmxyz/cryo).
cryo is the easiest way to extract blockchain data to parquet, csv, json, or python dataframes.
