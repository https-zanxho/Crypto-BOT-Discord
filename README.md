# Crypto-BOT-Discord

**Crypto-BOT-Discord** is a Discord bot that can track and show cryptocurrency prices, set price alerts, display charts, and more.

---

## 💡 Features

- Track prices of various cryptocurrencies in real-time
- Set alerts when tokens reach a specified price
- Display price charts and historical data
- Send notifications directly in Discord channels
- Support for multiple tokens and exchanges (depending on API availability)

---

## 📋 Requirements

- Discord account
- A server where the bot can be invited
- Python 3.9+ or Node.js (depending on implementation)
- Relevant API keys for price tracking (optional, depending on the data source)

---

## ▶️ How to run

1. Clone or download the repository.
2. Install dependencies:
   - For Python:
     ```bash
     pip install -r requirements.txt
     ```
   - For Node.js:
     ```bash
     npm install
     ```
3. Configure your bot token in the configuration file (`config.json` or `.env`).
4. Run the bot:
   - Python:
     ```bash
     python main.py
     ```
   - Node.js:
     ```bash
     node index.js
     ```
5. Invite the bot to your Discord server using the provided invite link.

---

## ⚡ Notes

- Make sure the bot has proper permissions in the server (e.g., send messages, embed links).
- For API-based features, check the API limits to avoid getting blocked.