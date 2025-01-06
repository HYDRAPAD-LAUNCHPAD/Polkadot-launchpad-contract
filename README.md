# Launchpad Contract

This repository contains the smart contract code for the **Launchpad** platform, a decentralized platform for token launches. The contract is designed to provide secure, transparent, and efficient token launching functionality, supporting both initial token offerings (ITOs) and other fundraising mechanisms.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Deployment](#deployment)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Launchpad Contract** is a smart contract written in Rust for Polkadot substrate, that allows projects to conduct token sales and crowdfunding. The contract includes various mechanisms like whitelisting participants, controlling sale parameters, and ensuring secure token transfers during the sale.

This smart contract is designed to be flexible and can be customized for different types of fundraising events, including presales, ICOs, and token swaps.

## Features

- **Whitelist Management:** Restrict participation to whitelisted addresses.
- **Token Sale Management:** Configure sale parameters such as price, cap, and duration.
- **Security:** Prevent common vulnerabilities in token sales such as reentrancy attacks and overflow/underflow issues.
- **Refunds:** Provide an option for refunds in case of unsuccessful fundraising.
- **Support for ERC-20 Tokens:** The contract supports the minting and transfer of ERC-20 tokens.

## Prerequisites

Before you begin, ensure that you have the following installed on your local machine:

- [Node.js](https://nodejs.org/) (>=14.0.0)
- [Truffle](https://www.trufflesuite.com/truffle) (for development and testing)
- [Ganache](https://www.trufflesuite.com/ganache) (for local blockchain simulation)
- [Solidity](https://soliditylang.org/) (for smart contract development)

## Installation

To get started with this repository, clone it to your local machine:

```bash
git clone https://github.com/HYDRAPAD-LAUNCHPAD/launchpad-contract.git
cd launchpad-contract
