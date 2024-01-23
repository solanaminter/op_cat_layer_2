# Layer 2 Token System

## Overview
This project is a conceptual implementation of a Layer 2 token system, enabling the creation and transfer of tokens with unique metadata off-chain for enhanced scalability and speed. The system is designed on top of a hypothetical blockchain where OP_CAT is enabled, allowing for the concatenation of data within script execution.

## Features
1. **Token Creation**: Users can generate unique tokens by concatenating token IDs with metadata.
2. **Transaction Phase (Off-chain)**: Token transfers are conducted off-chain, allowing for rapid and numerous transactions without congesting the blockchain.
3. **Closure Phase**: The final state of token balances is settled on-chain when the off-chain channel is closed.

## Getting Started

### Prerequisites
- Understanding of blockchain, Layer 2 technologies, and Bitcoin Script.
- Node.js and NPM installed for script execution simulation (in a real implementation, these scripts would be part of transactions on a blockchain).

