
# Blockchain Developer Bootcamp

A sample project demonstrating a basic Hardhat use case for blockchain development. This repository is designed as a hands-on learning tool for the Blockchain Developer Bootcamp curriculum and includes sample smart contracts, deployment scripts, tests, and an optional front-end integration—all built using Hardhat.

## Table of Contents
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

This repository serves as a practical introduction for blockchain developers. It demonstrates a simple Hardhat project that includes:

- **Smart Contracts:** Sample contracts written in Solidity.
- **Deployment Scripts:** Scripts to deploy contracts on a local or test network.
- **Testing Suite:** Unit tests to verify contract functionality.
- **Front-End Integration (Optional):** A basic front-end setup (located in the `public` and `src` folders) to interact with the deployed contracts.

## Prerequisites

Ensure you have the following installed before getting started:

- [Node.js](https://nodejs.org/) (v14 or higher is recommended)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Hardhat](https://hardhat.org/) (installed as a project dependency)

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nevets512/blockchain-developer-bootcamp.git
   cd blockchain-developer-bootcamp
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```
   Or, if you prefer using yarn:
   ```bash
   yarn install
   ```

## Project Structure

- **contracts/**: Contains Solidity smart contracts.
- **scripts/**: Deployment scripts for automating contract deployment.
- **test/**: Unit tests to ensure contract functionality.
- **src/**: (Optional) Source code for front-end integration.
- **public/**: (Optional) Static assets for the front-end application.
- **hardhat.config.js**: Hardhat configuration file.
- **package.json**: Project dependencies and scripts.
- **.gitignore**: Specifies intentionally untracked files (e.g., environment variables).

## Usage

### Hardhat Tasks

You can run various Hardhat tasks using npm scripts:

- **Display Help:**
  ```bash
  npx hardhat help
  ```
- **Run Tests:**
  ```bash
  npx hardhat test
  ```
- **Run Tests with Gas Reporting:**
  ```bash
  REPORT_GAS=true npx hardhat test
  ```
- **Start a Local Hardhat Node:**
  ```bash
  npx hardhat node
  ```
- **Deploy Contracts:**
  ```bash
  npx hardhat run scripts/deploy.js
  ```
### Running the Project

After deploying the contracts (locally or on a test network), you can interact with them via Hardhat or through the front-end (if applicable):

1. Deploy the contracts.
2. If using the front-end, you have two options:
   - **Local Development:** Serve the static files from the `public` folder using a tool like [live-server](https://www.npmjs.com/package/live-server) or any other web server of your choice.
   - **Production/Decentralized Hosting:** Deploy your front-end on [Fleek](https://fleek.co/), which hosts your static files on IPFS/Filecoin, providing a distributed and censorship-resistant experience.

## Testing

To verify the smart contracts, run the provided tests with:
```bash
npx hardhat test
```

## Deployment

Deploy the contracts to your desired network using:
```bash
npx hardhat run scripts/deploy.js
```
This command deploys your contracts to the network specified in your Hardhat configuration.

## Contributing

Contributions are welcome! If you would like to contribute:

1. **Fork** this repository.
2. **Create a new branch** for your feature or bug fix.
3. **Commit** your changes and **push** your branch.
4. Open a **pull request** with a detailed description of your changes.

For major changes, please open an issue first to discuss your proposed modifications.

## License

This project is open source and available under the [MIT License](LICENSE).  

## Acknowledgements

- [Hardhat](https://hardhat.org/) – An excellent development environment for Ethereum.
- [Ethereum](https://ethereum.org/) – The decentralized platform that powers smart contracts.
- All contributors and educators involved in the Blockchain Developer Bootcamp.

---
