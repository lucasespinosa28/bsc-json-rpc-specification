# bsc-json-rpc-specification
 
# Binance-Smart-Chain-json-rpc-specification

[View the Documentation]https://lucasespinosa28.github.io/bsc-json-rpc-specification/api-documentation/).

## Overview

This repository is the home of the Binance Smart Chain [OpenRPC](https://spec.open-rpc.org) document that describes the JSON-RPC interface to be implemented by client developers. It contains the tooling and scripts to automate producing artifacts for consuming the JSON-RPC API (docs, clients, etc).

## Introduction

Both Binance Smart Chain client developers and downstream dapp developers lack a formal Binance Smart Chain RPC specification. This proposal attempts to standardize such a specification in a way that's versionable, human-readable and machine-readable. It will improve the accuracy of documentation, API, and clients.

Binance Smart Chain clients can expose RPC endpoints with differing method signatures; this forces applications to work around method inconsistencies to maintain compatibility with various Binance Smart Chain RPC implementations.

Much of Binance Smart Chain effectiveness as an enterprise-grade application platform depends on its ability to provide a reliable and predictable developer experience.

## Specification

You can view the specification in documentation form [here]https://lucasespinosa28.github.io/bsc-json-rpc-specification/api-documentation/) or the raw **OpenRPC Document** [here](openrpc.json).

#### Preview

![eth_rpc_playground_docs_demo_eth_rpc](https://user-images.githubusercontent.com/364566/71375336-ba47f980-2572-11ea-9cd5-38c5149c485a.gif)


## Clients

The clients are generated from the **OpenRPC Document** `openrpc.json` in this repository, and can be used as an alternative to web3.js or ethers.js but for various languages:


## Documentation

[View the Documentation](https://lucasespinosa28.github.io/bsc-json-rpc-specification/api-documentation/).

### Contributing

Proposals to make method changes should be [made as an issue](https://help.github.com/en/articles/creating-an-issue).

How to contribute, build and release are outlined in [CONTRIBUTING.md](CONTRIBUTING.md), [BUILDING.md](BUILDING.md) and [RELEASING.md](RELEASING.md) respectively. Commits in this repository follow the [CONVENTIONAL_COMMITS.md](CONVENTIONAL_COMMITS.md) specification.

## Resources
- https://eips.ethereum.org/EIPS/eip-1901
- [Ethereum JSON-RPC Specification walkthrough](https://www.youtube.com/watch?v=EQW_wMi4tZE0)
- @bitpshr - https://github.com/ethereum/EIPs/pull/1474
- https://github.com/ethereum/EIPs/issues/1442
- https://github.com/ethereum/EIPs/issues/217
- https://github.com/ethereum/EIPs/issues/136
- https://ethereum-magicians.org/t/eip-remote-procedure-call-specification/1537/20
- https://github.com/etclabscore/ECIPs/issues/16
- https://github.com/ethereum/EIPs/pull/1901
- https://github.com/ethereum/EIPs/issues/1902
