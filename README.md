# XivTech
# 💹 Real-Time Crypto Price Tracker

A responsive React + Redux Toolkit application that simulates real-time crypto price updates. Displays live price changes for 5 cryptocurrencies with a clean UI.

## 🚀 Demo

![Demo GIF](demo.gif) <!-- Replace with actual demo.gif or link -->

## 🧰 Tech Stack

- **React**
- **Redux Toolkit**
- **CSS Modules**
- **Simulated WebSocket** using `setInterval`

## 🏗️ Architecture

- Redux state holds all asset data.
- Simulated real-time updates every 2 seconds.
- All UI updates driven by Redux state.
- Fully responsive layout.

## 🧪 Features

- 5 Crypto Assets: BTC, ETH, USDT, BNB, SOL
- Live updates: Price, 1h/24h % change, volume
- Color-coded % changes
- Static 7D charts
- Asset logos
- Responsive table

## 🛠️ Setup Instructions

```bash
git clone https://github.com/your-username/crypto-price-tracker.git
cd crypto-price-tracker
npm install
npm start
