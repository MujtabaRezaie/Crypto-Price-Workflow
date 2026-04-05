# Crypto-Price-Workflow (n8n)

This workflow provides real-time cryptocurrency prices through a Telegram bot using an external API.

Users start the bot and then send the name of a supported cryptocurrency such as Bitcoin, ETH, SOL, Tether, or DOGE. The workflow detects the requested coin, sends a request to the CoinGecko API, and retrieves the latest price in USD.

The result is then sent back to the user along with the current timestamp. The system is simple, fast, and designed for quick price lookups.

Requirements include n8n, Telegram Bot API, and access to the CoinGecko API.
