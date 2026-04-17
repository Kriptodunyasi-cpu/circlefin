# PromptPay (Arc Network Edition) 🧠💰

PromptPay is a decentralized AI marketplace optimized for the **Arc Network**. It leverages **Native USDC** to eliminate rigid subscription models, making AI services accessible through transparent, instant "pay-per-thought" micro-payments.

## 📉 The Problem: Subscription Fatigue
Today’s AI landscape is dominated by monthly subscription models. This creates barriers for users who only need occasional access and results in "subscription fatigue" where users pay for services they don't fully utilize.

## 💡 The Solution: Pay-Per-Thought
PromptPay disrupts this model by introducing a granular economy:
* **No Subscriptions:** Access premium AI without a monthly commitment.
* **Micro-Payments:** Pay only for what you use, down to the single prompt level.
* **Price Stability:** All interactions and gas fees are handled in **Native USDC (18 decimals)**, ensuring 100% cost predictability.

---

## 🚀 Mission & Vision

* **🌟 Mission:** Contributing to the decentralized future through individual innovation. By leveraging Arc Network's technical capabilities, I aim to create solutions that provide transparent and fair financial models for AI.
* **🔭 Vision:** To establish myself as an active and productive developer within the Arc Network ecosystem. This project is my first step toward growing alongside the community and building fundamental blocks on Arc.
* **🏗️ Developer's Note:** This project is currently developed solely by me. My motivation is to deeply understand Arc Network’s scalability and build tools that provide real utility.

---

## 🛠 Technical Stack & Highlights

* **Frontend:** React 19, TypeScript, Vite
* **Web3:** Wagmi & Viem (Optimized for Arc Custom Chain)
* **Network:** **Arc Testnet** (Native USDC Gas Platform)
* **AI Engine:** Gemini AI API (Google Cloud)
* **Smart Contracts:** Solidity ^0.8.20 (x402 Protocol Compatible)
* **Architecture:** Performance-oriented, modular, and security-first design.

---

## 🚀 Installation & Setup

### Prerequisites
- Node.js (Latest LTS)
- Gemini API Key ([Get it here](https://aistudio.google.com/))
- A Web3 Wallet (e.g., MetaMask)

### 1. Network Configuration (Arc Testnet)
Add the following network to your wallet:
| Property | Value |
|---|---|
| **Network Name** | Arc Testnet |
| **RPC URL** | https://rpc.testnet.arc.io |
| **Chain ID** | 1111 |
| **Currency Symbol** | USDC |
| **Block Explorer** | https://explorer.testnet.arc.io |

### 2. Environment Setup
Create a `.env` file in the root directory:
```env
# Required for AI responses
VITE_GEMINI_API_KEY=your_gemini_api_key

# Required for self-referential links / callbacks
VITE_APP_URL=https://your-app-url.com

# Optional: Custom Arc RPC URL
VITE_ARC_RPC_URL=https://rpc.testnet.arc.io
```

### 3. Local Development
```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

## 📜 Smart Contract Deployment
To deploy the contract to Arc Network, use Foundry:
```bash
forge create --rpc-url https://rpc.testnet.arc.io \
  --private-key $YOUR_PRIVATE_KEY \
  contracts/PromptPay.sol:PromptPay
```

---
Built with passion for the **Arc Network** ecosystem. 🌐🤖
