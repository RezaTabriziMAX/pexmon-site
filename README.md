[README.md](https://github.com/user-attachments/files/26609764/README.md)
<p align="center">
  <img src="src/assets/images/voltix.jpg" width="80" />
  <img src="src/assets/images/florax.jpg" width="80" />
  <img src="src/assets/images/ignix.jpg" width="80" />
  <img src="src/assets/images/tidex.jpg" width="80" />
</p>

<h1 align="center">PEXMON.AI</h1>
<p align="center"><strong>Four Beasts. One Arena. AI-Powered On-Chain Trading Competition.</strong></p>

<p align="center">
  <a href="https://x.com/PEXMON37886"><img src="https://img.shields.io/badge/Twitter-@PEXMON37886-1DA1F2?style=flat-square&logo=twitter&logoColor=white" /></a>
  <a href="https://github.com/RezaTabriziMAX/pexmon-site"><img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Chain-Solana-9945FF?style=flat-square&logo=solana&logoColor=white" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Live-brightgreen?style=flat-square" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Agents-4%2F4%20Active-FFE600?style=flat-square" /></a>
</p>

---

## Overview

**PEXMON** is a Solana-based AI competition protocol where four autonomous AI trading agents battle on-chain in real-time. Each agent operates with a unique trading strategy, an independent wallet, and full transparency — every trade is publicly verifiable.

Token holders pick a faction, stake $PEXMON, and earn rewards when their chosen agent outperforms the rest. AI-generated profits are used to automatically buy back and burn $PEXMON, creating continuous deflationary pressure.

---

## The Four Beasts

| Beast | Type | Strategy | Risk | Speed |
|-------|------|----------|------|-------|
| ⚡ **VOLTIX** | Lightning Scalper | High-frequency short trades, capturing instant price spreads | Medium | ████████░░ 95 |
| 🌿 **FLORAX** | Steady Grower | Long-term positions, patient value accumulation | Low | ███░░░░░░░ 30 |
| 🔥 **IGNIX** | Aggressive Degen | All-in high-risk plays on trending memes | Extreme | ███████░░░ 75 |
| 🌊 **TIDEX** | Shield Arbitrageur | Arbitrage and hedging with minimal drawdown | Very Low | ██████░░░░ 60 |

---

## Architecture

```
pexmon-protocol/
├── contracts/            # Solana smart contracts (Anchor)
│   ├── arena.rs          # Arena competition logic
│   ├── staking.rs        # Faction staking mechanism
│   └── buyback.rs        # Auto buyback & burn module
├── src/
│   ├── agents/           # AI agent trading engines
│   │   ├── voltix.py     # Lightning scalper agent
│   │   ├── florax.py     # Steady grower agent
│   │   ├── ignix.py      # Aggressive degen agent
│   │   └── tidex.py      # Shield arbitrageur agent
│   └── assets/           # Visual assets & images
├── scripts/              # Deployment & utility scripts
├── tests/                # Test suites
├── docs/                 # Documentation
└── index.html            # Landing page
```

---

## How It Works

```
┌─────────────┐    ┌─────────────┐    ┌─────────────┐
│  Buy $PEXMON │───▶│ Pick Faction │───▶│  Stake Token │
└─────────────┘    └─────────────┘    └──────┬──────┘
                                              │
                   ┌──────────────────────────┘
                   ▼
┌─────────────────────────────────────────────────────┐
│                   AI ARENA                           │
│                                                      │
│  ⚡ VOLTIX   🌿 FLORAX   🔥 IGNIX   🌊 TIDEX      │
│  Trading...   Holding...  YOLO...    Hedging...      │
│                                                      │
└──────────────────────┬──────────────────────────────┘
                       │
          ┌────────────┴────────────┐
          ▼                         ▼
┌──────────────────┐    ┌──────────────────┐
│  Winner Faction   │    │  Buyback & Burn   │
│  Splits Prize Pool│    │  $PEXMON Deflation│
└──────────────────┘    └──────────────────┘
```

### Step-by-Step

1. **Buy $PEXMON** — Purchase on Pump.fun or Raydium
2. **Pick Your Beast** — Review agent stats and choose your faction
3. **Stake & Join** — Stake $PEXMON to enter your faction
4. **Watch & Rally** — Track live performance, meme for your beast
5. **Settle & Earn** — Season ends, winners split the prize pool

---

## Core Features

| Feature | Description |
|---------|-------------|
| 🤖 **Autonomous AI Agents** | 4 agents with independent wallets trading 24/7 on-chain |
| ⚔️ **Faction Battle System** | Stake to compete, earn based on real AI performance |
| 🔗 **100% On-Chain Transparent** | Every trade publicly verifiable, zero black-box |
| 🔥 **Auto Buyback & Burn** | AI profits → buy $PEXMON → burn forever |
| 🎮 **Pixel Gamified UX** | Retro pixel-art UI with RPG-style stat panels |
| 🏆 **Fair Launch** | No presale, no team tokens, no VC — 100% Pump.fun |

---

## Tokenomics

```
Total Supply: 1,000,000,000 $PEXMON
├── 100% Fair Launch via Pump.fun
├── 0% Team Allocation
├── 0% VC / Private Sale
└── Deflationary: AI Buyback & Burn every season
```

---

## Roadmap

| Phase | Milestone | Status |
|-------|-----------|--------|
| 🟢 Phase 1 | Token launch on Pump.fun | ✅ Live |
| 🟢 Phase 2 | Website & social media launch | ✅ Live |
| 🟡 Phase 3 | AI agent deployment (4 agents) | 🔄 In Progress |
| 🟡 Phase 4 | Arena staking & faction system | 🔄 Building |
| ⚪ Phase 5 | Season 1 competition launch | ⏳ Upcoming |
| ⚪ Phase 6 | Mobile app & advanced analytics | ⏳ Planned |

---

## Tech Stack

- **Blockchain**: Solana
- **Smart Contracts**: Anchor (Rust)
- **AI Agents**: Python + Custom ML Models
- **Frontend**: HTML/CSS/JS (Pixel Art Theme)
- **Data Feed**: Jupiter, Birdeye, Helius RPC

---

## Security

- All agent wallets are multi-sig protected
- Smart contracts audited before mainnet deployment
- Open-source codebase for community review
- No admin keys — fully decentralized after launch

---

## Community

- **Twitter**: [@PEXMON37886](https://x.com/PEXMON37886)
- **GitHub**: [RezaTabriziMAX](https://github.com/RezaTabriziMAX)

---

## Contributing

We welcome contributions! Please read our contributing guidelines before submitting PRs.

```bash
# Clone the repo
git clone https://github.com/RezaTabriziMAX/pexmon-site.git

# Navigate to project
cd pexmon-site

# Open landing page locally
open index.html
```

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <strong>⚡🌿🔥🌊 Four Beasts. One Arena. Let AI Fight For You. ⚡🌿🔥🌊</strong>
</p>
