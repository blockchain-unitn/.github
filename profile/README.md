# SkyLedger

**Blockchain for Secure and Transparent Unmanned Traffic Management (UTM)**  
_A project by [blockchain-unitn](https://github.com/blockchain-unitn)_

---

## 🚀 Project Overview

**SkyLedger** is a blockchain-powered UTM (Unmanned Traffic Management) platform designed to ensure **security**, **transparency**, **efficiency**, and **compliance** in drone operations. Leveraging the Avalanche blockchain, SkyLedger addresses the critical challenges in airspace management as drone adoption scales globally.

---

## 🛑 The Challenge

### Current Gaps in UAV Traffic Management:

- **Security & Trust:** Verifying drone identities and securing sensitive flight data.
- **Transparency & Accountability:** Tracking flight paths, incidents, and responsibilities.
- **Efficiency:** Automating authorization processes and minimizing delays.
- **Regulatory Compliance:** Adhering to dynamic aviation regulations with immutable logs.

---

## 💡 The Solution: SkyLedger UTM

SkyLedger integrates **blockchain technology** into drone traffic systems for:

### 🔐 Core Functions

- **Flight Data Logging:** Immutable, blockchain-based "black boxes" for drones.
- **Decentralized Airspace Sharing:** Real-time coordination between multiple operators.
- **Smart Contract Automation:** Flight authorizations, emergency protocols, and compliance checks.
- **Secure Identity with NFTs:** Each drone is assigned a verifiable NFT-based identity.

### 🔄 Real-World Use Case: Drone Delivery Network

SkyLedger enables:

- **Automated Pre-Flight Authorization:** Validates pilot, drone, cargo, and route against regulations.
- **Immutable Route Logging:** Records all authorizations and changes on-chain.
- **Emergency Handling:** Smart contracts auto-trigger alerts, re-routing, and privilege penalties.

---

## 🔧 Technical Architecture

### 🧱 Blockchain Layer

- **Blockchain:** [Avalanche](https://www.avax.network/)
- **Type:** Private subnet for UTM
- **Smart Contracts:** Built on Solidity and deployed on Avalanche C-Chain

### 📦 On-Chain Data

- **NFTs for Drone ID:** Certification, ownership, history
- **Flight Permissions:** Purpose, payload, and regulatory compliance
- **Route Logs & Deviations:** Only critical events stored on-chain
- **Emergency Alerts:** Triggered via smart contracts

### 🧠 Smart Contract Functionalities

- **Flight Authorization**
- **Real-Time Compliance Checks**
- **Emergency Protocol Execution**
- **Audit Trail & History Logging**

---

## 🌐 Why Avalanche?

- **High Throughput:** Sub-second finality and thousands of TPS
- **Low Fees:** Optimized for high-frequency drone interactions
- **EVM Compatible:** Easy migration from Solidity
- **Subnet Support:** Custom governance and performance
- **Eco-Friendly:** Proof-of-Stake consensus
- **Secure & Scalable:** Strong finality and cross-chain integration

---

## 💼 Value Proposition

| Benefit              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| 🔒 Security          | Cryptographic verification and tamper-proof logs                            |
| 🧾 Transparency       | Verifiable records of all operations                                        |
| ⚙️ Automation         | Smart contract-based workflows for speed and accuracy                      |
| 📋 Compliance         | Immutable audit trails to satisfy regulators                               |
| 🚨 Risk Mitigation   | Real-time alerts and automatic emergency handling                           |

---

## 🧪 How to Test the MVP

To test the SkyLedger MVP:

1. **Clone the Core Blockchain Layer and follow the instructions**
   ```bash
   git clone -b production https://github.com/blockchain-unitn/skyledger-blockchain.git
   ```
   
2. **Clone the Backend Module and follow the instructions**
    ```bash
    git clone -b production https://github.com/blockchain-unitn/skyledger-backend.git
    ```
    
3. **Clone the FrontEnd Module and follow the instructions**
    ```bash
    git clone -b production https://github.com/blockchain-unitn/skyledger-frontend.git
    ```
    
4. **Clone the Simulation UTM Backend Module and follow the instructions**
    ```bash
    git clone -b production https://github.com/blockchain-unitn/backend-utm.git
    ```
    
