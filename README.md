# 🌱 DeESG

Decentralised ESG Evaluation using IoT and LLM with Incentivised Green Token (GTK)

## 📌 Problem Statement

1. Current ESG evaluations are potentially biased, as scores may be manipulated by organisations to appear better than they are, aimed at attracting more funding and investments.
2. There’s not enough data to train AI models. Plus, current ESG evaluation relies heavily on self-reported data. More trustworthy data is needed to train AI models for ESG rating.
3. Companies are not incentivised enough to improve or maintain their ESG scores, which hinders positive environmental impact.

## ✅ Solution

### 🌐 Decentralised ESG Rating System

1. Leverage AI clustering method to classify company ESG risk levels and generate ESG ratings, eliminate the need for human evaluation and likelihood of human bias.
2. a. **E:** Using IoT devices to allow trustless process for data collection, using sensors on edge devices to gather environmental data (e.g. greenhouse emissions and electricity consumption).

b. **S, G:** A forum thread allows all company members to participate, with upvotes/downvotes representing the company's sentiment (qualitative data), ensuring balance and reducing tampered company data (S, G). Leverage FHE(Fully Homomorphic Encryption) for anonymity. 3. **GreenToken (GTK)** tokenomics system incentivises companies to become more sustainable and ethical, while also supporting governance in the sustainability and regenerative finance sector.

## 🚀 Features

1. **AI-powered ESG Rating System:** Utilizes advanced AI algorithms to analyze and rate companies based on their ESG performance.
2. **IoT-enabled Data Collection:** Implements IoT devices to collect real-time environmental data from company premises.
3. **Secure and Anonymous Forum:** Enables company members to participate in discussions and provide feedback securely and anonymously.
4. **GreenToken (GTK) Tokenomics:** Introduces a tokenomics system to incentivize companies to improve their ESG performance and support governance in the sustainability and regenerative finance sector.

## 💻 Tech Stack

### Frontend

Languages: TypeScript, Javascript

Framework: Next.js

Styling: TailwindCSS, Google Fonts

---

### Backend

Smart Contracts: Solidity

Blockchain Frameworks: Web3.js, Ethers.js

Networks: Scroll Sepolia Testnet, Zircuit Testnet, Polygon Amoy, Linea Sepolia Testnet

---

### Data Integration and Automation

**Chainlink:**

Automation: Schedule data retrieval from IoT sensor devices.

Functions: Perform off-chain computations (e.g., validating IoT data) and send verified results on-chain.

Smart Contracts: Manage reward distribution and storage of verified IoT data on the blockchain.

---

### Decentralized Data Retrieval

**The Graph:**

Build customized subgraphs to index and query on-chain IoT data.

Enable efficient data feeds to the AI clustering model for ESG evaluation.

---

### Privacy and Governance

**Inco Protocol**

Leverage Fully Homomorphic Encryption (FHE) to enable privacy-preserving governance mechanisms.

Facilitate anonymous employee participation (comments, upvotes/downvotes) in the ESG forum.

---

### Storage

**IPFS**

Store raw IoT sensor data and metadata in a decentralized, immutable manner.
Provide accessibility to data for on-chain analysis and audits.

---

### On Chain AI

**Model Deployment:**

Deploy clustering models for ESG evaluation using pre-trained frameworks.

Integrate with blockchain for on-chain inference.

---

### Ledger

Withdraw GTK from Smart Wallet

---

## Smart Contract Addresses:

###Smart Contract Functions:

## Links

1. DeESG Landing Page:
2.
