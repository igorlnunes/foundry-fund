# Foundry - Fund me

Welcome to the **Foundry - Fund me** repository! This repository contains [brief description of the project].

## Table of Contents

- [Getting Started](#getting-started)
- [Quickstart](#quickstart)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

These instructions will help you set up the project locally on your machine. To get a copy of the project up and running on your local system, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/igorlnunes/foundry-fund.git
    cd foundry-fund
    ```

2. **Install the dependencies:**

    ```bash
    npm install
    ```

## Quickstart

Once you have the project set up, here's a quick way to [brief description of what this section covers]:

**Install Foundry**

    ```bash
    forge build
    ```

### MIT License

[The MIT License](https://opensource.org/licenses/MIT) is a permissive open source license that allows you to use, modify, and distribute the code in your own projects. When using this license, you are not obligated to share your modifications or derivative works of the project's code.

#### How to use the MIT License

1. Include the License Text:
   Make sure to include a copy of the MIT License text in your project's repository. You can do this by creating a file named `LICENSE` at the root of your project and pasting the contents of the [MIT License](https://opensource.org/licenses/MIT).

2. Add the License Badge:
   It's a good practice to include a license badge in your README to inform others about the project's licensing. You can use shields.io to generate a badge. Here's an example Markdown code for the MIT License badge:
   

## Foundry

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
