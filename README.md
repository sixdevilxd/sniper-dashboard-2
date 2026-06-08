# 🚀 Solana Token Scanner - AI-Powered Memecoin Discovery

[![Python 3.11+](https://img.shields.io/badge/python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Telegram Bot](https://img.shields.io/badge/Telegram-Bot-blue?logo=telegram)](https://telegram.org/)

Discover, analyze, and track Solana memecoins dengan kekuatan AI. Scanner lengkap seperti Birdeye dengan fitur AI insights, risk scoring, dan real-time alerts.

## ✨ Fitur Utama

- 🔍 **Smart Search** - Fuzzy matching untuk token discovery
- 📊 **Real-time Data** - Price, volume, liquidity dari multiple sources
- 🤖 **AI Analysis** - GPT-4 powered insights & recommendations
- ⚠️ **Risk Scoring** - Honeypot detection, holder concentration analysis
- ⭐ **Watchlist** - Track favorite tokens dengan alerts
- 📈 **Trending** - Top movers by 24h volume
- 💾 **Portfolio** - Performance tracking & analytics

## 🎯 Quick Start

### Prerequisites
- Python 3.11+
- Telegram Bot Token
- API Keys (Helius, OpenAI, DexScreener, Solscan)

### Installation

```bash
# Clone repository
git clone https://github.com/yourusername/solana-token-scanner.git
cd solana-token-scanner

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# or: venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Setup environment
cp .env.example .env
# Edit .env dengan API keys Anda
