# Layer 2 Token System with OP_CAT

## Overview
This project implements a Layer 2 (L2) token system on top of a blockchain (hypothetical implementation assuming OP_CAT is enabled). It allows users to create tokens with unique metadata and transact off-chain to ensure fast and scalable transactions, with final settlement on the blockchain.

### Features
1. **Token Creation**: Users can create tokens by concatenating a unique token ID with metadata (like token name, symbol, and issuance date).
2. **Transaction Phase (Off-chain)**: Users transact with these tokens off-chain, maintaining the state of token balances privately.
3. **Closure Phase**: Final settlement of token balances on the main chain when the off-chain channel is closed.

## Getting Started

### Prerequisites
- A basic understanding of blockchain and Layer 2 technologies.
- [Node.js](https://nodejs.org/en/) and NPM installed.

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/layer2-token-system.git
