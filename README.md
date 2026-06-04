<p align="center">
  <img src="https://img.icons8.com/emoji/96/000000/pig-bank-emoji.png" alt="AutoEarn" width="96">
</p>

<h1 align="center">🐷 AutoEarn</h1>

<p align="center">
  <b>开源自动化赚/省钱助手</b><br>
  行情预警 · 价格监控 · 自动通知 · 统计看板
</p>

<p align="center">
  <img src="https://img.shields.io/badge/python-3.9%2B-blue" alt="Python">
  <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey" alt="Platform">
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen" alt="PRs Welcome">
</p>

---

## ✨ 功能

| 功能 | 说明 |
|------|------|
| 📈 行情预警 | BTC/ETH/美股突破目标价自动通知 |
| 💰 价格监控 | 商品降价到目标价以下弹窗提醒 |
| 🤖 Telegram Bot | 推送到手机，出门在外也能收到 |
| 🖥️ 桌面通知 | Windows 原生弹窗 |
| 📊 统计看板 | 省/赚金额记录和可视化 |
| ⏰ 自动调度 | 每 30 分钟自动检查一轮 |

## 🚀 快速开始

```bash
# 1. 安装依赖
pip install requests schedule rich

# 2. 初始化（生成配置 + 示例数据）
python autoearn.py init

# 3. 启动自动化
python autoearn.py run
```

## 📖 命令

| 命令 | 说明 |
|------|------|
| `init` | 初始化配置（含 BTC/ETH/苹果股价示例） |
| `run` | 前台启动自动化（每 30 分钟检查） |
| `daemon` | 后台窗口运行 |
| `status` | 查看看板（累计省钱、预警统计） |

## 🤖 Telegram 推送

```bash
# Windows
set TELEGRAM_TOKEN=123456:ABC-DEF
set TELEGRAM_CHAT_ID=123456789
python autoearn.py run

# macOS / Linux
TELEGRAM_TOKEN=xxx TELEGRAM_CHAT_ID=xxx python autoearn.py run
```

## 📁 文件

| 文件 | 说明 |
|------|------|
| `autoearn.py` | 主程序 |
| `autoearn_config.json` | 配置文件（自动生成） |
| `autoearn_data.csv` | 省钱/赚钱记录 |
| `autoearn_log.txt` | 运行日志 |

## 🛠️ 自定义配置

编辑 `autoearn_config.json`，可以:

- 添加任意加密货币对: `DOGE/USDT`, `SOL/USDT`
- 添加美股代码: `TSLA`, `NVDA`, `AMD`
- 添加商品价格监控
- 调整检查频率和预警阈值

参考 [examples/config.example.json](examples/config.example.json)

## 🤝 贡献

欢迎 Issue 和 PR!

1. Fork 本仓库
2. 创建分支: `git checkout -b feature/xxx`
3. 提交: `git commit -m "feat: 添加 XXX"`
4. PR → 合并 → 你的头像会出现在 Contributors 列表 🎉

## 📄 许可证

[MIT](LICENSE)

## ⭐ 历史 Star

如果这个项目对你有帮助，请给一个 Star ⭐ 支持一下!
