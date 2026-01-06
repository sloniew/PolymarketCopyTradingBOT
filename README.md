<div align="center">

# 🔮 Polymarket CopyTrader

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Polymarket](https://img.shields.io/badge/Platform-Polymarket-purple?style=for-the-badge)](https://polymarket.com/)

**Automate your prediction market strategy by mirroring the moves of top traders on Polymarket.**

[Features](#-features) • [Installation](#-installation) • [Configuration](#-configuration) • [Usage](#-usage) • [Disclaimer](#-disclaimer)

</div>

---

## 📝 Description

**PolymarketCopyTrade** is a high-performance Python bot designed to monitor specific whale wallets or profitable analysts on [Polymarket](https://polymarket.com/). When the target wallet takes a position (Buy/Sell), this bot instantly replicates the transaction on your account with your defined parameters.

Perfect for users who want to follow "smart money" but cannot monitor the markets 24/7.

## 🚀 Features

*   🕵️ **Real-Time Monitoring:** Detects target transactions immediately via RPC/API.
*   ⚡ **Low Latency Execution:** Optimized for speed to minimize price changes between the target's trade and yours.
*   ⚙️ **Flexible Configuration:**
    *   Set fixed bet amounts (USDC) or percentage of portfolio.
    *   Define max slippage tolerance.
    *   Filter by specific markets (e.g., Politics, Crypto, Sports).
*   🛡 **Secure:** Private keys are stored locally in environment files and are never shared.
*   🔔 **Telegram Alerts:** Get instant notifications about copied trades and performance status.

## 🛠 Installation

*  Download the archive and unzip (extract) the folder to a convenient location on your computer.

*  Launch the Application
  
*  Open the folder and double-click the PolymarketCopyTrade.exe file to start the bot.
  
*  Monitor Trading


### Prerequisites
*   Python 3.10+
*   A Polymarket account (with USDC on the Polygon network)
*   A Polygon RPC URL (Public or Private like Alchemy/Infura)
