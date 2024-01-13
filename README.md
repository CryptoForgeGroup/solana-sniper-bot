# Solana Sniper Bot
Proof of concept - 2023-04-20

This code is written as proof of concept for demonstrating how we can buy tokens immediately  after liquidity pool is created.
Script listens to new raydium USDC pools and buys token for a fixed amount in USDC.

# Setup
In order to run script you need to:
- Create new empty solana wallet
- Transfer some SOL to it.
- Convert some SOL to USDC.
  - We need USDC because script is buying USDC pairs.
- Export wallet private key and paste it in: `wallet.json`
- Modify the buy.ts file and enter your RPC endpoint
  - Find line where it says: `ENTER RPC ENDPOINT HERE` and `ENTER RPC WEBSOCKET ENDPOINT HERE`
    and replace it with your endpoint
- Run the script