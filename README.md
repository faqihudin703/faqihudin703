<div align="center">

# Faqihuddin — Santara Labs
### Blockchain Infrastructure Engineer · Cirebon, Indonesia

*Semester 6 Informatics student building decentralized infrastructure for the Indonesian market.*
*Solo founder. Real products. Live on testnet/devnet.*

[![Colosseum Frontier 2026](https://img.shields.io/badge/Colosseum_Frontier-2026-f5a623?style=flat-square)](https://colosseum.com/frontier)
[![Solana Network State](https://img.shields.io/badge/Solana_Network_State-Spring_2026-9945FF?style=flat-square)](https://ns.com)
[![Superteam Indonesia](https://img.shields.io/badge/Superteam-Indonesia-39d98a?style=flat-square)](https://superstudy.fun)

</div>

---

## About

I started from networking and server administration, then pivoted into blockchain out of curiosity — and ended up building a full DeFi + AI ecosystem under **Santara Labs** in under a year. Everything is self-hosted on a homelab built from recycled hardware, running 24/7 behind zero open inbound ports.

Background in **network engineering** (Mikrotik, Tailscale, Cloudflare Zero Trust) directly shapes how I think about blockchain infrastructure — decentralized, sovereign, and security-first at every layer.

Currently building **Santara Weather Oracle** for the Colosseum Frontier hackathon — an on-chain weather data oracle for Indonesia sourcing from BMKG at village/district granularity, with 5 active nodes and 10K+ aggregation rounds completed.

---

## Santara Labs — Product Ecosystem

All products are live on testnet/devnet, upgradeable via proxy, and actively maintained.

| Product | Chain | Description |
|---|---|---|
| 🌤️ **Santara Weather Oracle** | Solana Devnet | BMKG weather data on-chain · multi-node consensus · 52 feeds · village-level granularity · tiered subscription API |
| 🏛️ **Santara BI Oracle** | Solana Devnet | Bank Indonesia official forex rates on-chain · 1 currency = 1 PDA · public infrastructure for Indonesian DeFi |
| 🌉 **Santara Terminal** | ETH L1 & L2s ↔ Solana | Cross-chain bridge + DEX · custom relay architecture · event-driven message passing |
| 🔄 **Santara Protocol** | Base Sepolia | ETH/IDR direct swap via custom oracle (Indodax) · yield-bearing deposits · deflationary reward token |
| 🏦 **Santara Station** | Arbitrum Sepolia | ETH lending with USDC collateral · oracle-based pricing from Binance · fixed-term borrowing |
| 🧠 **Santara Cortex** | Solana ↔ 0G Galileo | First cross-chain AI NFT protocol (iNFT) · Solana as identity layer · 0G as AI compute · chain abstraction via Phantom |

---

## Tech Stack

| Kategori | Teknologi |
| :--- | :--- |
| **Blockchain** | Rust / Anchor · Solidity · Hardhat · Ethers.js v6 · Transparent Proxy (EIP-1967) · PDA / Account Model · Ethereum · Solana · Arbitrum · Base · 0G Galileo |
| **Backend & Data** | Node.js · Python FastAPI · PM2 · Docker · Supabase / PostgreSQL · Signature-cursor Indexer · Multi-tier REST API · Polling-based Oracle Node |
| **Infrastructure & Networking** | Mikrotik + 3-layer NAT · Tailscale mesh VPN (one-way sharing) · Cloudflare Tunnel (Zero Trust) · Zero open inbound ports · Homelab: Acer V5-431P + STB HG680P · UPS · aaPanel |
| **Frontend** | React / Vite · Tailwind CSS · Ethers.js · @solana/web3.js · Borsh (browser-native) |

---

## Homelab Infrastructure

Running production-grade infrastructure on recycled hardware:

- **Acer V5-431P** — Intel Pentium 2117U, 12GB RAM, 500GB HDD → main server (Docker + PM2)
- **STB HG680P** — ARM Cortex-A53, 2GB RAM → lightweight containers + Tailscale subnet router
- **Network** — Mikrotik router · 3 NAT layers · zero exposed ports · Cloudflare Tunnel for public access
- **Oracle Nodes** — 1 homelab anchor + 4 AWS EC2 (Free Tier) · all zero inbound · one-way Tailscale

Everything runs without downtime, without cloud dependency for core infrastructure.

---

## Oracle Node Architecture

**BMKG API** (3-hourly) <br>
⬇ <br>
**6 Oracle Nodes** (homelab + AWS EC2) <br>
⬇ *submit_data()* <br>
**Santara Weather Oracle Program** (Solana Devnet) <br>
⬇ *median aggregation (threshold consensus)* <br>
**On-chain FeedData PDA** (per location) <br>
⬇ <br>
**Node.js Indexer** (signature cursor, 1-hour polling) <br>
⬇ <br>
**Supabase PostgreSQL** <br>
⬇ <br>
**Python FastAPI** (tiered access: Starter / Basic / Pro / Business / Enterprise) <br>
⬇ <br>
**React Dashboard + Public API**

**Live stats:** `10,071 rounds` · `52 feeds` · `26,247 tx` · `99.99% success rate`

---

## Currently

- 🏆 **Colosseum Frontier Hackathon** (Apr 6 – May 11, 2026) — Santara Weather Oracle
- 🌐 **Solana Network State Spring 2026** — virtual participant, building alongside ecosystem founders
- 📚 **Semester 6 Informatika** — while managing all of the above

---

## Open For

- Blockchain infrastructure internships
- Oracle / data infrastructure collaborations
- DeFi protocol technical consulting
- Anything that involves building something real

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=faqihudin703&show_icons=true&theme=radical&count_private=true&hide_border=true&bg_color=0a0a0a&title_color=f5a623&icon_color=f5a623&text_color=e8e8e8" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs?username=faqihudin703&layout=compact&theme=radical&hide_border=true&bg_color=0a0a0a&title_color=f5a623&text_color=e8e8e8" width="49%" />

<br><br>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=faqihudin703&theme=react-dark&hide_border=true&area=true&radius=16" width="100%" alt="Contribution Graph" />

</div>
