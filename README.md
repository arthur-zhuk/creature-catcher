# Creature Catcher

![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![AssemblyScript](https://img.shields.io/badge/AssemblyScript-007AAC?style=for-the-badge&logo=assemblyscript&logoColor=white)
![NEAR](https://img.shields.io/badge/NEAR-00D9FF?style=for-the-badge&logo=near&logoColor=white)

Early MVP of a simple smart contract deployed on the NEAR blockchain. Catch creatures in this Web3 game built with AssemblyScript for the NEAR Protocol.

## Features

- **NEAR Protocol**: Deployed on NEAR blockchain
- **Smart Contracts**: Written in AssemblyScript
- **View Methods**: Read-only contract methods
- **Change Methods**: State-modifying contract methods
- **Contract Storage**: Basic on-chain storage

## Tech Stack

- **Blockchain**: NEAR Protocol
- **Smart Contracts**: AssemblyScript
- **Language**: TypeScript

## Installation

```bash
git clone https://github.com/arthur-zhuk/creature-catcher.git
cd creature-catcher
yarn install
```

## Usage

### Build Contracts

```bash
yarn build:release
```

### Run Tests

```bash
yarn test
```

### Test Commands

```bash
yarn test:unit      # Run unit tests only
yarn test:simulate  # Run simulation tests only
```

## Getting Started

1. Clone this repository
2. Run `yarn install`
3. Run `yarn build:release` (required before testing)
4. Run `yarn test` to run all tests

## Project Structure

```
src/
├── sample/              # Sample contract
│   ├── __tests__/      # Unit tests
│   └── ...
└── ...
```

## Development

```bash
yarn build          # Verify build status
yarn clean          # Clean build folder
yarn test           # Run all tests
yarn test:unit      # Unit tests only
yarn test:simulate  # Simulation tests only
```

## Documentation

- Contract interface: See `/src/sample/README`
- Unit testing: See `/src/sample/__tests__/README`
- Simulation tests: See `/simulation/README`

## License

MIT
