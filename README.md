To run this bot:

Install dependencies:




bashCopynpm install telegram-bot-api ethers bitcoinjs-lib dotenv

Create .env file:

CopyTELEGRAM_TOKEN=your_telegram_bot_token
BRIDGE_ADDRESS=your_bridge_contract_address
BTC_NODE_URL=your_btc_node_url
ETH_RPC_URL=your_eth_rpc_url
PRIVATE_KEY=your_private_key

Run the bot:

bashCopynode bot.js
