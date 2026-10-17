# PrivyMarket

**A blockchain-based, privacy-preserving data-sharing and rewards platform.**

PrivyMarket aims to enable secure data authorization, transparent reward mechanisms, and privacy-aware data sharing. The project explores how blockchain technology can support controlled access to personal data while protecting user privacy.

> **Development status:** Early development. The repository currently contains the initial project structure and Hardhat starter code. PrivyMarket-specific functionality is not yet implemented.

## Project Structure

```text
PrivyMarket/
├── backend/       # Backend services and APIs
├── bench/         # Performance benchmarks
├── contracts/     # Solidity smart contracts and tests
├── docs/          # Documentation and learning notes
├── firmware/      # Device firmware
├── web/            # Frontend application
├── zk/             # Zero-knowledge proof components
├── ignition/       # Hardhat deployment modules
├── scripts/        # Development and transaction scripts
├── test/           # Automated tests
├── .gitignore      # Git exclusions
├── hardhat.config.ts
├── package.json
├── package-lock.json
└── tsconfig.json
```

## Technology Stack

- **Blockchain:** Solidity, Hardhat 3
- **Development:** Node.js, npm, TypeScript
- **Ethereum interaction:** Viem
- **Version control:** Git and GitHub

Additional technologies will be introduced as the project develops.

## Current Progress

- [x] GitHub repository created
- [x] Initial project folder structure created
- [x] Hardhat development environment initialized
- [x] Starter test suite executed successfully
- [ ] Blockchain fundamentals documented
- [ ] PrivyMarket smart contracts implemented
- [ ] Backend APIs implemented
- [ ] Frontend application developed
- [ ] Privacy and zero-knowledge components explored
- [ ] Application integration and end-to-end testing

## Starter Contracts

The following files are currently included for development environment verification:

- `contracts/Counter.sol` — Example Solidity counter contract.
- `contracts/Counter.t.sol` — Example Solidity tests.

These are temporary Hardhat starter examples, not the actual PrivyMarket implementation. They are retained until project-specific contracts are developed.

## Getting Started

### Prerequisites

Install Node.js and npm, then verify your installation:

```bash
node --version
npm --version
git --version
```

### 1. Clone the repository

```bash
git clone https://github.com/Tusharkr110/PrivyMarket.git
cd PrivyMarket
```

### 2. Install dependencies

```bash
npm install
```

### 3. Verify Hardhat

```bash
npx hardhat --version
```

### 4. Run the tests

```bash
npx hardhat test
```

The current starter tests verify the example contract and its associated functionality. Passing these tests does not yet validate PrivyMarket-specific features.

## Development Guidelines

- Keep project-specific code organized in its corresponding directory.
- Write tests for smart contracts before integrating them with the application.
- Never commit private keys, wallet seed phrases, API secrets, or populated environment files.
- Keep dependencies reproducible through `package-lock.json`.
- Document significant changes and learning progress in `docs/`.
- Verify tests before committing changes.

## Learning Log

| Day | Activity | Status |
|---|---|---|
| Day 1 | Repository setup and Hardhat initialization | Complete |
| Day 2 | Blockchain fundamentals and documentation | Pending |

## License

No license has been specified yet. Licensing will be decided as the project develops.
