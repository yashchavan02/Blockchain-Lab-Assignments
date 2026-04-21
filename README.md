# Blockchain Lab Assignments

A collection of blockchain development assignments covering smart contracts, Web3 integration, IPFS storage, and DAO implementation.

## Assignments

### Assignment 1: MessageStore Smart Contract
Simple Solidity smart contract to store and retrieve messages on the blockchain.

- **Network:** Sepolia Testnet
- **Tech:** Solidity, Remix IDE, MetaMask

[Details](assignment-1/README.md)

---

### Assignment 2: Deploy on Polygon
Deploy the MessageStore contract on Polygon Amoy Testnet.

- **Network:** Polygon Amoy
- **Tech:** Solidity, Remix IDE, MetaMask

[Details](assignment-2/README.md)

---

### Assignment 3: Web Interface
Build a DApp with a web interface to interact with the smart contract.

- **Network:** Sepolia Testnet
- **Tech:** HTML, CSS, ethers.js, MetaMask

[Details](assignment-3/README.md)

---

### Assignment 4: IPFS Storage
Decentralized file storage using IPFS and Pinata.

- **Tech:** HTML, CSS, JavaScript, Pinata API

[Details](assignment-4/README.md)

---

### Assignment 5: DAO
Decentralized Autonomous Organization with proposal creation, voting, and execution.

- **Network:** Sepolia Testnet
- **Tech:** Solidity, Remix IDE, MetaMask

[Details](assignment-5/README.md)

---

## Quick Start

1. Install MetaMask browser extension
2. Get testnet ETH from faucets:
   - Sepolia: https://faucet.sepolia.io
   - Polygon: https://faucet.polygon.technology
3. Open the assignment folder and follow its README

## Project Structure

```
Blockchain-Lab-Assignments/
├── assignment-1/     # Smart contract basics
├── assignment-2/     # Polygon deployment
├── assignment-3/     # Web3 frontend
├── assignment-4/     # IPFS storage
├── assignment-5/     # DAO implementation
└── README.md        # This file
```

## Notes

- API keys in assignment-4 must be entered manually (not hardcoded)
- DAO functions (createProposal, executeProposal) are owner-only