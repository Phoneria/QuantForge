# QuantForge — Prompt-to-Backtest Platform

> **TÜBİTAK-Supported Startup** | Live & Active

QuantForge turns plain English into fully executable trading strategy backtests. No coding required. Just describe your strategy, and QuantForge handles the rest — parsing your intent, generating the logic, and running it against historical market data using our proprietary backtest engine.

---

## The Problem

Algorithmic trading has a high barrier to entry. Retail traders with strong market intuition can't act on their ideas without knowing how to code. Existing platforms require programming knowledge, rigid templates, or expensive subscriptions just to test a hypothesis.

QuantForge removes that barrier entirely.

---

## How It Works

```
User types: "Buy when RSI drops below 30 and price is above 200 EMA, 
             sell when RSI crosses 70 or stop loss hits 2%"

QuantForge:
  1. Parses natural language intent via fine-tuned LLM
  2. Translates into structured strategy logic
  3. Runs against historical data on proprietary backtest engine
  4. Returns performance metrics, equity curve, drawdown analysis
```

---

## Core Features

### Natural Language Strategy Parser
- Fine-tuned LLM translates user intent into executable trading logic
- Supports complex multi-condition entry/exit rules
- Handles risk management parameters (stop loss, take profit, position sizing)

### Proprietary Backtest Engine
- Built from scratch for speed and accuracy
- Supports tick-level and OHLCV data
- Realistic execution simulation (slippage, commission, partial fills)
- Multi-asset and multi-timeframe support

### AI-Enhanced Strategy Optimization
- Self-trained models for adaptive parameter tuning
- Risk/reward optimization across historical regimes
- Dynamic position sizing based on volatility

### Live Strategy Validation
- Strategies are tested against real-market conditions
- Proven track record: live hedging algorithm averaging ~5% monthly return over 5+ consecutive months, no month below 4%

---

## Tech Stack

| Layer | Stack |
|---|---|
| NLP / LLM | Fine-tuned transformer, LangChain |
| Backtest Engine | Python (proprietary) |
| Trading Integration | NinjaTrader, MetaTrader 5 |
| AI Models | PyTorch, Scikit-learn |
| Data | Multi-exchange OHLCV, tick data |

---

## Team

4-person founding team with backgrounds in:
- Algorithmic trading (live Nasdaq strategies, 5+ months real-market)
- AI/ML Engineering (ASELSAN, Baykar Technologies)
- Full-stack platform development

---

## Status

```
[x] Natural language strategy parser
[x] Proprietary backtest engine
[x] Live trading validation
[x] Risk optimization models
[ ] Public beta launch
[ ] Multi-exchange support
[ ] Strategy marketplace
```

---

## Research & Support

Developed under **TÜBİTAK** (The Scientific and Technological Research Council of Turkey) R&D support program.

---

## Contact

**Izzet Ahmet** — Co-Founder & AI Lead
- GitHub: [@Phoneria](https://github.com/Phoneria)
- LinkedIn: [linkedin.com/in/izzet-ahmet-702176219](https://linkedin.com/in/izzet-ahmet-702176219)
- Email: izzet.ahmet216@gmail.com

---

> *"Your edge shouldn't be limited by your ability to code."*
