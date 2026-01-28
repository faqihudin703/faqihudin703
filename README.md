# Hi there, I'm Faqihudin 👋

I'm an Informatics student transitioning into a **Blockchain Infrastructure Engineer**. I combine my strong background in network engineering and server automation to build resilient, decentralized systems.

My focus has evolved from private labs to **architecting interoperability protocols for the Superchain** (Lisk, Base, Optimism) and **exploring the frontier of Modular AI solutions** by merging Decentralized Compute (DePIN) with Intelligent NFTs (iNFT) on the 0G Network.

---

## 🛠️ Tech Stack & Core Competencies

<table>
  <tr>
    <td valign="top" width="50%">
      <strong>⛓️ Blockchain & Web3 Development</strong>
      <ul>
        <li><strong>Smart Contracts:</strong> Solidity, OpenZeppelin (Upgradeable/Proxy, AccessControl)</li>
        <li><strong>Standards:</strong> ERC-20 (DeFi), ERC-721/1155 (NFT), ERC-7857 (AI Agent NFT)</li>
        <li><strong>Advanced Integrations:</strong> Account Abstraction (Coinbase Smart Wallet SDK)</li>
        <li><strong>Architecture:</strong> Lock-and-Mint Bridges, Dual-Engine DEX, <strong>Modular DA Layers</strong></li>
        <li><strong>Frameworks:</strong> Hardhat, Ethers.js v6</li>
        <li><strong>Ecosystems:</strong> Ethereum, Lisk, Base, Optimism, Arbitrum, 0G (ZeroGravity)</li>
        <li><strong>Frontend DApp:</strong> React.js, Vite, Tailwind CSS, OnchainKit</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <strong>🔌 Infrastructure, AI & DevOps</strong>
      <ul>
        <li><strong>Relayer Engine:</strong> Custom Node.js Event Listeners (Concurrency & Idempotency)</li>
        <li><strong>AI Compute (DePIN):</strong> Hosting Local LLM (Qwen) via <strong>0G Storage/Compute Node</strong></li>
        <li><strong>Oracle Engineering:</strong> Custom Real-time Data Feeds (CEX API to On-Chain)</li>
        <li><strong>Server Management:</strong> Linux (Ubuntu/Armbian), Docker & Compose</li>
        <li><strong>Networking:</strong> Advanced MikroTik, Tailscale Mesh, Cloudflare Tunnel (Zero Trust)</li>
        <li><strong>Observability:</strong> Grafana, Prometheus, PM2 Monitoring</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

### 1. Santara Terminal (Lisk Hackathon Build)
A high-performance liquidity layer bridging **Lisk Sepolia**, **Base Sepolia** and **Sepolia**.
- **Architecture:** "Lock-and-Mint" bridge with automated **Node.js Relayers**.
- **Economic Model:** Implemented **Protocol Fee (Payable Functions)** logic, allowing the bridge to generate revenue in Native ETH from every Lock/Burn transaction.
- **Security:** Built-in **Idempotency** checks to prevent double-spending and replay attacks.
- **Stack:** React (Vite), Ethers v6, Hardhat, Dockerized Relayer.

### 2. Santara Protocol (Base Hackathon Build)
An end-to-end decentralized banking infrastructure on **Base Sepolia** designed to bring the Indonesian Rupiah (IDR) on-chain.
- **Direct Settlement Engine:** Solves the friction of "double conversion" (IDR → USD → ETH) by enabling direct swaps between ETH and a Rupiah-pegged stablecoin (**IDRX**) using a custom AMM.
- **Proprietary Oracle Node:** Engineered a secure, self-hosted Oracle bot that aggregates **Real-Time IDR/ETH rates** from **Indodax** and injects them on-chain with deviation-based updates.
- **Sustainable Yield Architecture:** Implements a circular economy where users stake IDRX in the **NXS Vault** to earn yield, backed by a **Treasury Redemption** mechanism (burn NXS for USDC).
- **Next-Gen UX:** Fully integrated with **Coinbase Smart Wallet** (Passkeys) and **OnchainKit**, removing seed phrase friction for mass adoption in emerging markets.

### 3. 0G Intelligent NFT (iNFT) & AI-Compute Lab
An experimental **DePIN (Decentralized Physical Infrastructure Network)** implementation on the **0G Galileo Testnet**, proving the concept of on-chain AI Agents.
- **DePIN Architecture:** Repurposed a local **Acer Server** to act as a decentralized **AI Compute Node** within the 0G Galileo Network.
- **Local LLM Inference:** The server hosts and runs the **Qwen** model locally, powering the intelligence behind the NFTs without relying on centralized APIs like OpenAI.
- **Interactive iNFTs:** Built a dApp where users can **Mint iNFTs**, transfer ownership, and **Chat directly with the AI Agent** attached to the NFT (processed via the local 0G Compute Node).
- **Status:** Functional Prototype / Workshop Build.

### 4. Homelab Omni-Chain Ecosystem
An experimental DeFi & NFT platform connecting 5 chains: **Sepolia, Hoodi, Base Sepolia, Arbitrum Sepolia, and Optimism Sepolia**.
- **Dual-Engine DEX:** Integrated Standard AMM ($x*y=k$) on all chain for volatiles and **StableSwap** invariant only Sepolia for pegged assets.
- **Cross-Chain NFT Bridge:** Enables users to bridge NFTs between L1 and L2s while maintaining ownership history.
- **Dynamic Metadata with Rate-Limiting:** Users can customize NFT traits (e.g., Renaming). To secure this, I built a dedicated **Node.js API Service** that acts as a **Rate Limiter**, preventing spam and abuse during the metadata update process.

---

## 🔧 Ongoing Engineering & Research

- **🌉 The Superchain Vision:** Expanding infrastructure to support the **Optimism Superchain** stack, ensuring seamless asset routing between OP Sepolia, Base Sepolia, and Lisk Sepolia.
- **🧠 Modular AI Integration:** Researching high-throughput data availability on **0G Galileo Testnet** to store massive AI datasets on-chain.
- **🛡️ Infrastructure Hardening:** Running critical blockchain infrastructure on a low-power **Armbian STB cluster**, secured behind **Cloudflare Tunnels** to ensure high availability without exposing public IPs.
- **📊 Production-Grade Relayers:** Moving from simple polling to **Event-Driven Architectures** capable of handling RPC latency, Chain Reorgs, and nonce management automatically.

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=faqihudin703&show_icons=true&theme=radical&count_private=true" alt="GitHub Stats" width="100%" />
  <br>
  
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=faqihudin703&layout=compact&theme=radical" alt="Top Languages" width="100%" />
  <br>
  
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=faqihudin703&theme=react-dark&hide_border=true&area=true&radius=16" width="100%" alt="Contribution Graph" />
</p>
