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
- [Akula](https://github.com/akula-bft/akula).
Ethereum execution client - deprecated.

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
- [kzg](https://github.com/ralexstokes/kzg).
A library for KZG commitments over BLS12-381 in Rust.
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
- [Rundler](https://github.com/alchemyplatform/rundler).
An ERC-4337 Bundler in Rust - high-performance, modular implementation of an ERC-4337 bundler.
- [ethers-userop](https://github.com/qi-protocol/ethers-userop/).
An ether-rs middleware to craft user operations.
- [UoIndexer](https://github.com/zsluedem/UoIndexer).
User operation indexer for ERC-4337.

## zkEVM

- [Zeth](https://github.com/risc0/zeth).
A "Type 0" zkEVM. Prove validity of Ethereum blocks using RISC Zero's zkVM.
- [zkevm-circuits](https://github.com/privacy-scaling-explorations/zkevm-circuits).
Circuits for zkEVM.

## Statelessness

- [rust-verkle](https://github.com/crate-crypto/rust-verkle).
This is a proof of concept implementation of Verkle Tries.
- [verkle-block-sample](https://github.com/gballet/verkle-block-sample).
Example of a block root with a Verkle state root.

## Layer 2

### Arbitrum
- [Stylus](https://github.com/OffchainLabs/stylus-sdk-rs).
Rust Smart Contracts on Arbitrum.

### Aztec
- [noir-lang](https://github.com/noir-lang/noir).
Noir is a domain specific language for zero knowledge proofs.

### Optimism
- [op-reth](https://github.com/anton-rs/op-reth).
Optimism + Reth.
- [Magi](https://github.com/a16z/magi).
A blazing fast OP Stack rollup client.
- [op-revm](https://github.com/anton-rs/op-revm).
Optimism + Revm.
- [cannon-rs](https://github.com/anton-rs/cannon-rs).
An alternative implementation of the OP Stack's Cannon, a MIPS emulator for the EVM.
- [optimism-rs](https://github.com/refcell/optimism-rs).
Scaling Ethereum, but this time in rust.

### Polygon
- [plonky2](https://github.com/0xPolygonZero/plonky2).
Plonky2, a SNARK implementation based on techniques from PLONK and FRI.

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
- [starknet_in_rust](https://github.com/lambdaclass/starknet_in_rust).
A Rust implementation of Starknet execution logic.

### ZkSync
- [zksync-era](https://github.com/matter-labs/zksync-era).
zkSync era.
- [era-sync_vm](https://github.com/matter-labs/era-sync_vm).
Circuit Implementation of zkVM for zkSync Era.

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
