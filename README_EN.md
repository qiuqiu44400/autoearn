<p align="center">
  <img src="https://img.icons8.com/emoji/96/000000/pig-bank-emoji.png" alt="AutoEarn" width="96">
</p>

<h1 align="center">🐷 AutoEarn</h1>

<p align="center">
  <b>Open-source automated money-saving assistant</b><br>
  Price Alerts · Monitoring · Notifications · Dashboard
</p>

<p align="center">
  <img src="https://img.shields.io/badge/python-3.9%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey" alt="Platform">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="PRs Welcome">
</p>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📈 Price Alerts | BTC/ETH/Stocks — notified when targets are hit |
| 💰 Price Monitoring | Track products, get alerts on price drops |
| 🤖 Telegram Bot | Push notifications to your phone |
| 🖥️ Desktop Notifications | Native Windows popups |
| 📊 Dashboard | Stats & visualization of savings |
| ⏰ Auto-scheduler | Checks every 30 minutes automatically |

## 🚀 Quick Start

```bash
# 1. Install dependencies
pip install requests schedule rich

# 2. Initialize (creates config + examples)
python autoearn.py init

# 3. Start monitoring
python autoearn.py run
```

## 📖 Commands

| Command | Description |
|---------|-------------|
| `init` | Create config with example alerts (BTC/ETH/AAPL) |
| `run` | Start automated monitoring (every 30min) |
| `daemon` | Run in background window |
| `status` | View dashboard (total saved, alert stats) |

## 🤖 Telegram Integration

```bash
# Windows
set TELEGRAM_TOKEN=123456:ABC-DEF
set TELEGRAM_CHAT_ID=123456789
python autoearn.py run

# macOS / Linux
TELEGRAM_TOKEN=xxx TELEGRAM_CHAT_ID=xxx python autoearn.py run
```

## 📁 Files

| File | Description |
|------|-------------|
| `autoearn.py` | Main program |
| `autoearn_config.json` | Configuration (auto-generated) |
| `autoearn_data.csv` | Savings/earnings records |
| `autoearn_log.txt` | Runtime logs |

## 🛠️ Customization

Edit `autoearn_config.json` to:

- Add any crypto pair: `DOGE/USDT`, `SOL/USDT`
- Track stocks: `TSLA`, `NVDA`, `AMD`
- Monitor product prices
- Adjust check intervals & alert thresholds

See [examples/config.example.json](examples/config.example.json)

## 🤝 Contributing

Issues and PRs are welcome!

1. Fork this repo
2. Create branch: `git checkout -b feature/xxx`
3. Commit: `git commit -m "feat: add XXX"`
4. PR → merge → your avatar in Contributors list 🎉

## 📄 License

[MIT](LICENSE)

## ⭐ Star History

If you find this project useful, please give it a Star ⭐!
