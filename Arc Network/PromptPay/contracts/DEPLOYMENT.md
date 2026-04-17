[DEPLOYMENT.md](https://github.com/user-attachments/files/26806148/DEPLOYMENT.md)
# PromptPay Smart Contract Deployment (Arc Testnet)

This guide explains how to deploy the `PromptPay.sol` contract to the Arc Testnet.

## Prerequisites
- [Foundry](https://book.getfoundry.sh/getting-started/installation) installed.
- A wallet with Arc Testnet USDC (Gas token).
- Your Private Key.

## Deployment Command

Run the following command in your terminal:

```bash
forge create --rpc-url https://rpc.testnet.arc.io \
  --private-key YOUR_PRIVATE_KEY \
  contracts/PromptPay.sol:PromptPay
```

## Verification (Optional)

To verify the contract on ArcScan:

```bash
forge verify-contract <DEPLOYED_ADDRESS> \
  contracts/PromptPay.sol:PromptPay \
  --chain-id 5042002 \
  --watch
```

## Contract Interface (ABI)

The contract address should be updated in `src/constants.ts` once deployed.
