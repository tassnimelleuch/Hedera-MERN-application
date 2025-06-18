# 💊 Decentralized Drug Supply Chain Transparency System

A decentralized application (DApp) using the **MERN stack** and **Hedera Hashgraph** to ensure transparency, traceability, and security in the **drug supply chain**. It incorporates **IPFS** for storing drug metadata, and smart contracts deployed using **Remix IDE**. The application uses **Ethers.js** and **MetaMask** for blockchain interaction, with a **role-based access** model.

---

## 🚀 Features

- 🔐 **Role-based access control** (Manufacturer, Distributor, Pharmacy, Regulator)
- 📦 **Track and trace** drug batches across the supply chain
- 🧾 **Immutable records** via Hedera Hashgraph
- 🗂️ **Drug metadata stored on IPFS** (e.g., certificates, packaging info)
- 🌐 **React.js** frontend with MetaMask wallet support
- 🔧 Smart contracts written in **Solidity** and deployed using **Remix IDE**
- 📡 Integration with **Ethers.js** for blockchain communication

---

## 🛠️ Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Blockchain Layer**: Hedera Hashgraph (Testnet)
- **Smart Contracts**: Solidity (Remix IDE)
- **Wallet & Blockchain Integration**: MetaMask + Ethers.js
- **File Storage**: IPFS (via Infura or Web3.Storage)
---

## 🗂️ Drug Metadata & IPFS

Each drug batch includes:
- Batch details
- Certificates (PDF/JSON)
- Manufacturer info


## 📄 Smart Contracts

Smart contracts manage:
- Role assignment and verification
- Drug registration with metadata CID
- Authorized transfer between roles
- Immutable history on Hedera

Contracts were developed in **Solidity** and deployed via **Remix IDE** using the Hedera plugin.

---

## 🛡️ Security

- Role-based restrictions to ensure only valid actors access specific actions
- IPFS ensures metadata immutability and off-chain storage
- Hedera provides fast, tamper-proof, and carbon-negative consensus


