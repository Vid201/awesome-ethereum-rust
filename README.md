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
- [ZKP and zkEVM](#zkp-and-zkevm)
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
- [libp2p](https://github.com/libp2p/rust-libp2p).
The Rust implementation of the libp2p networking stack.

## Execution

- [Reth](https://github.com/paradigmxyz/reth).
Ethereum execution client.
- [Akula](https://github.com/akula-bft/akula).
Ethereum execution client - deprecated.
- [ranger](https://github.com/Rjected/ranger).
Ranger is an ethereum p2p client capable of interacting with peers without a full node.

## EVM - Ethereum Virtual Machine

- [Revm](https://github.com/bluealloy/revm/).
Rust Ethereum virtual machine (revm) Is EVM written in rust that is focused on speed and simplicity.
- [jitevm](https://github.com/paradigmxyz/jitevm).
Convert evm bytecode to native machine code and go vroom.
- [evm-disassembler](https://github.com/ckoopmann/evm-disassembler).
Rust library to disassemble evm bytecode.
- [create2crunch](https://github.com/0age/create2crunch).
A Rust program for finding salts that create gas-efficient Ethereum addresses via CREATE2.
- [balls](https://github.com/Philogy/balls).
A DSL for generating optimal EVM bytecode.
- [evm-inspectors](https://github.com/paradigmxyz/evm-inspectors).
EVM Execution Hooks for revm.
- [revmc](https://github.com/paradigmxyz/revmc).
JIT and AOT compiler for the Ethereum Virtual Machine, built on Revm.

## Core

- [alloy](https://github.com/alloy-rs/alloy).
Alloy connects applications to blockchains. Transports, Middleware, and Networks for the Alloy project. Rewrite of ethers-rs.
- [alloy core](https://github.com/alloy-rs/core).
High-performance, well-tested & documented core libraries for Ethereum.
- [chains](https://github.com/alloy-rs/chains).
Canonical type definitions for EIP-155 chains.
- [ethers-rs](https://github.com/gakonst/ethers-rs/).
Complete Ethereum library and wallet implementation.
- [Reth](https://github.com/paradigmxyz/reth).
Modular, contributor-friendly and blazing-fast implementation of the Ethereum protocol.
- [ethers-reth](https://github.com/SorellaLabs/ethers-reth/).
An ether-rs middleware to access reth's db directly, bypassing JSON-RPC.
- [rust-web3](https://github.com/tomusdrw/rust-web3).
Ethereum JSON-RPC multi-transport client. Rust implementation of web3 library.
- [ssz-rs](https://github.com/ralexstokes/ssz-rs).
Implementation of Ethereum's ssz.
- [ethereum_ssz](https://github.com/sigp/ethereum_ssz).
SimpleSerialize (SSZ) implementation optimised for speed and security.
- [ssz_types](https://github.com/sigp/ssz_types).
List, vector and bitfield types for SSZ.
- [rlp](https://github.com/alloy-rs/rlp).
Fast implementation of Ethereum RLP serialization.
- [enr](https://github.com/sigp/enr).
This crate contains an implementation of an Ethereum Node Record (ENR) as specified by EIP-778.
- [Rust Crypto](https://github.com/RustCrypto).
Dozens of popular crates which provide pure Rust implementations of cryptographic algorithms.
- [uint](https://github.com/recmo/uint).
Rust Uint crate using const-generics.

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
- [kateth](https://github.com/jacobkaufmann/kateth).
Ethereum KZG.

## PBS - Proposer-Builder Separation

- [mev-rs](https://github.com/ralexstokes/mev-rs/).
A gateway to a network of block builders.
- [evangelion](https://github.com/jacobkaufmann/evangelion/).
A prototype Ethereum block builder.
- [ethers-flashbots](https://github.com/onbjerg/ethers-flashbots).
An Ethers middleware for submitting Flashbots bundles.
- [Artemis](https://github.com/paradigmxyz/artemis).
A simple, modular, and fast framework for writing MEV bots.
- [Hindsight](https://github.com/flashbots/hindsight).
Retroactively estimate Uniswap-ish MEV on Flashbots MEV-Share by simulating backrun-arbitrages.
- [mev-share-rs](https://github.com/paradigmxyz/mev-share-rs).
Rust client library for Flashbots MEV-share.
- [mev-inspect-rs](https://github.com/flashbots/mev-inspect-rs).
Discover historic Miner Extractable Value (MEV) opportunities.
- [suave-andromeda-revm](https://github.com/flashbots/suave-andromeda-revm).
Andromeda revm execution service - EVM with precompiles used internally by SUAVE for key management and boostrapping kettles.

## Account Abstraction

- [Silius](https://github.com/Vid201/silius/).
ERC-4337 (Account Abstraction) - modular and efficient bundler implementation.
- [Rundler](https://github.com/alchemyplatform/rundler).
An ERC-4337 Bundler in Rust - high-performance, modular implementation of an ERC-4337 bundler.
- [ethers-userop](https://github.com/qi-protocol/ethers-userop/).
An ether-rs middleware to craft user operations.
- [UoIndexer](https://github.com/zsluedem/UoIndexer).
User operation indexer for ERC-4337.

## ZKP and zkEVM

- [Zeth](https://github.com/risc0/zeth).
A "Type 0" zkEVM. Prove validity of Ethereum blocks using RISC Zero's zkVM.
- [zkevm-circuits](https://github.com/privacy-scaling-explorations/zkevm-circuits).
Circuits for zkEVM.
- [halo2](https://github.com/privacy-scaling-explorations/halo2).
Implementation of halo2 zkSNARK proof system.
- [chiquito](https://github.com/privacy-scaling-explorations/chiquito).
DSL for Halo2 circuits.
- [lambdaworks](https://github.com/lambdaclass/lambdaworks).
The library for kids who wanna learn how to do SNARKs and learn other cryptographic stuff too.
- [noir-lang](https://github.com/noir-lang/noir).
Noir is a domain specific language for zero knowledge proofs.
- [sp1](https://github.com/succinctlabs/sp1).
A performant, 100% open-source, contributor-friendly zkVM.
- [sp1-reth](https://github.com/succinctlabs/sp1-reth).
A performant, type-1 zkEVM written in Rust & SP1.

## Statelessness

- [rust-verkle](https://github.com/crate-crypto/rust-verkle).
This is a proof of concept implementation of Verkle Tries.
- [verkle-block-sample](https://github.com/gballet/verkle-block-sample).
Example of a block root with a Verkle state root.

## Layer 2

### Arbitrum

- [Stylus](https://github.com/OffchainLabs/stylus-sdk-rs).
Rust Smart Contracts on Arbitrum.

### Optimism

- [op-reth](https://github.com/anton-rs/op-reth).
Optimism + Reth.
- [Reth AlphaNet](https://github.com/paradigmxyz/alphanet).
Reth AlphaNet is a testnet OP Stack-compatible rollup aimed at enabling experimentation of bleeding edge Ethereum Research.
- [Magi](https://github.com/a16z/magi).
A blazing fast OP Stack rollup client.
- [op-revm](https://github.com/anton-rs/op-revm).
Optimism + Revm.
- [cannon-rs](https://github.com/anton-rs/cannon-rs).
An alternative implementation of the OP Stack's Cannon, a MIPS emulator for the EVM.
- [optimism-rs](https://github.com/refcell/optimism-rs).
Scaling Ethereum, but this time in rust.
- [op-up](https://github.com/anton-rs/op-up).
Composable OP Stack Orchestration.
- [durin](https://github.com/anton-rs/durin).
A Rust library for creating solvers in the OP Stack's dispute protocol.
- [op-alloy](https://github.com/alloy-rs/op-alloy).
Optimism alloy types.

### Polygon

- [plonky2](https://github.com/0xPolygonZero/plonky2).
Plonky2, a SNARK implementation based on techniques from PLONK and FRI.

### Scroll

- [scroll-prover](https://github.com/scroll-tech/scroll-prover).
Scroll's zkEVM rust crates.

### Starknet

- [Starknet Foundry](https://github.com/foundry-rs/starknet-foundry).
Blazing fast toolkit for developing Starknet contracts.
- [Madara](https://github.com/keep-starknet-strange/madara).
Madara is a blazing fast Starknet sequencer, based on substrate.
- [Papyrus](https://github.com/starkware-libs/papyrus).
Papyrus is a Starknet full node written.
- [starknet-rs](https://github.com/xJonathanLEI/starknet-rs).
Complete Starknet library.
- [Cairo](https://github.com/starkware-libs/cairo).
Cairo is the first Turing-complete language for creating provable programs for general computation.
- [cairo-vm](https://github.com/lambdaclass/cairo-vm).
cairo-vm is a Rust implementation of the Cairo VM.
- [starknet_in_rust](https://github.com/lambdaclass/starknet_in_rust).
A Rust implementation of Starknet execution logic.
- [types-rs](https://github.com/starknet-io/types-rs).
Starknet Rust types.
- [Stone Prover](https://github.com/starkware-libs/stone-prover).
Stone prover - this repository contains a prover and a verifier for STARKs, and in particular for the CPU AIR underlying the CairoZero programming language.

### zkSync

- [zksync-era](https://github.com/matter-labs/zksync-era).
zkSync era.
- [era-sync_vm](https://github.com/matter-labs/era-sync_vm).
Circuit Implementation of zkVM for zkSync Era.

### Taiko

- [raiko](https://github.com/taikoxyz/raiko).
Multi-proofs for Taiko. SNARKS, STARKS and Trusted Execution Enclave.

### Fuel

- [Sway](https://github.com/FuelLabs/sway).
Sway is a language developed for the Fuel blockchain. It is heavily inspired by Rust and aims to bring modern language development and performance to the blockchain ecosystem.
- [fuel-core](https://github.com/FuelLabs/fuel-core).
Rust full node implementation of the Fuel v2 protocol.
- [fuels-rs](https://github.com/FuelLabs/fuels-rs).
Rust SDK for Fuel.

### Aztec

- [aztec-nr](https://github.com/AztecProtocol/aztec-nr).
Aztec-nr is a Noir framework for smart contracts on Aztec.

### Other

- [zenith-rs](https://github.com/init4tech/zenith-rs).
Rust types and services for Zenith (next-gen rollup system).

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
- [huff-rs](https://github.com/huff-language/huff-rs).
A low-level assembly language for the Ethereum Virtual Machine built in blazing-fast pure rust.

## Data Analytics

- [cryo](https://github.com/paradigmxyz/cryo).
cryo is the easiest way to extract blockchain data to parquet, csv, json, or python dataframes.

## Misc

- [block-explorers](https://github.com/foundry-rs/block-explorers).
Bindings for the etherscan API and other block explorers.
