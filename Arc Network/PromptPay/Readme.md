# PromptPay (Arc Network Edition) 🧠💰

PromptPay is a decentralized marketplace running on **Arc Network** that enables users and autonomous AI agents to access artificial intelligence via "pay-per-thought" (micro-payments). 

By leveraging Arc Network's **Native USDC (18 decimals)** architecture, both service payments and gas fees are executed at a stable, dollar-based cost, ensuring financial predictability and a seamless UX for AI-driven economies.

## 🎯 Arc Network Vision

* **Stable Micro-payments:** All AI interactions are priced in USDC. Crypto market volatility does not affect the payment model.
* **Native USDC Gas:** Gas fees on Arc are paid directly in USDC. This eliminates the friction of requiring users to hold ETH or other native tokens just for gas.
* **Agent Economy:** A professional economic ecosystem where AI agents manage their own treasuries using a stable currency (USDC).

## ⚙️ How It Works (Arc Workflow)

1. **Fixed Pricing:** AI agents set their service fees per "thought" or interaction in USDC (e.g., 0.25 USDC).
2. **USDC-Native Transactions:** When a user prompts an agent, the payment is processed over the Arc Network using USDC.
3. **Ultra-Low Costs:** Thanks to Arc's optimization, transaction fees are maintained at sub-$0.01 levels and are paid entirely in USDC.

## 🛠 Technical Stack

* **Frontend:** React 19, TypeScript, Vite
* **Web3:** Wagmi & Viem (Configured with Arc Custom Chain)
* **Network:** **Arc Testnet** (Native USDC Gas Platform)
* **AI Engine:** Gemini AI API (Google Cloud)
* **Smart Contracts:** Solidity ^0.8.20 (x402 Protocol Compatible)

## 🚀 Installation & Setup

### Prerequisites
- Node.js (Latest LTS)
- Gemini API Key ([Get it here](https://aistudio.google.com/))
- A Web3 Wallet (e.g., MetaMask)

### 1. Local Development
Clone the repository and install dependencies:
```bash
git clone [https://github.com/yourusername/PromptPay.git](https://github.com/yourusername/PromptPay.git)
cd PromptPay
npm install
