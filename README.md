# Nado Contracts ⚡

> EVM smart contract implementation for the Nado Protocol — a DeFi protocol core built with Solidity and Hardhat.

[![Solidity](https://img.shields.io/badge/Solidity-0.8.x-363636?logo=solidity)](https://docs.soliditylang.org/)
[![Hardhat](https://img.shields.io/badge/Hardhat-build-yellow)](https://hardhat.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## What It Does

This repository contains the core EVM smart contracts for the Nado Protocol — a DeFi protocol. The contracts implement Nado's on-chain logic and are structured for Hardhat-based compilation, testing, and deployment.

## Repository Structure

```
nado-contracts/
├── core/                   # EVM implementation of Nado core
│   ├── contracts/          # Solidity source files
│   ├── tasks/              # Hardhat tasks
│   ├── hardhat.config.ts
│   └── package.json
└── .github/                # CI workflows
```

## Screenshot

<!-- TODO: add a screenshot of `yarn compile` output here -->
![Compile output](docs/screenshot.png)

## Prerequisites

- Node.js >= 16
- [Yarn](https://yarnpkg.com/)

## Installation

```bash
git clone https://github.com/kalialucard/nado-contracts.git
cd nado-contracts/core
yarn install
```

## Usage

```bash
# Compile contracts
yarn compile

# Run tests
yarn test

# Deploy to a local Hardhat network
yarn hardhat node
yarn hardhat deploy --network localhost
```

## Security

This repository is a research/audit reference. Do not deploy unaudited contracts to mainnet. Review `core/VERIFICATION.md` for contract verification details.

## License

[MIT](LICENSE) © kalialucard
