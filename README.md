# Hi there, I'm Faqihudin 👋

I'm an Informatics student transitioning into a **Blockchain Infrastructure Engineer**. I combine my strong background in network engineering and server automation to build resilient, decentralized systems.

My focus has evolved from private labs to **architecting interoperability protocols for the Superchain** (Lisk, Base, Optimism) and building full-stack DeFi ecosystems that bridge the gap between Layer-1 and Layer-2.

---

## 🛠️ Tech Stack & Core Competencies

<table>
  <tr>
    <td valign="top" width="50%">
      <strong>⛓️ Blockchain & Web3 Development</strong>
      <ul>
        <li><strong>Smart Contracts:</strong> Solidity, OpenZeppelin (Upgradeable/Proxy, AccessControl)</li>
        <li><strong>Standards:</strong> ERC-20 (DeFi), ERC-721 & ERC-1155 (NFT Bridge)</li>
        <li><strong>Architecture:</strong> Lock-and-Mint Bridges, Dual-Engine DEX (AMM + StableSwap)</li>
        <li><strong>Frameworks:</strong> Hardhat, Ethers.js v6</li>
        <li><strong>Ecosystems:</strong> Ethereum, Lisk, Base, Arbitrum, Optimism</li>
        <li><strong>Frontend DApp:</strong> React.js, Vite, Tailwind CSS</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <strong>🔌 Infrastructure & DevOps</strong>
      <ul>
        <li><strong>Relayer Engine:</strong> Custom Node.js Event Listeners (Concurrency & Idempotency)</li>
        <li><strong>Server Management:</strong> Linux (Ubuntu/Armbian), Docker & Compose</li>
        <li><strong>Networking:</strong> Advanced MikroTik, Tailscale Mesh, Cloudflare Tunnel (Zero Trust)</li>
        <li><strong>API Middleware:</strong> Node.js Rate-Limiter (Spam Protection)</li>
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

### 2. Homelab Omni-Chain Ecosystem
An experimental DeFi & NFT platform connecting 5 chains: **Sepolia, Hoodi, Base Sepolia, Arbitrum Sepolia, and Optimism Sepolia**.
- **Dual-Engine DEX:** Integrated Standard AMM ($x*y=k$) for volatiles and **StableSwap** invariant for pegged assets.
- **Cross-Chain NFT Bridge:** Enables users to bridge NFTs between L1 and L2s while maintaining ownership history.
- **Dynamic Metadata with Rate-Limiting:** Users can customize NFT traits (e.g., Renaming). To secure this, I built a dedicated **Node.js API Service** that acts as a **Rate Limiter**, preventing spam and abuse during the metadata update process.

---

## 🔧 Ongoing Engineering & Research

- **🌉 The Superchain Vision:** Expanding infrastructure to support the **Optimism Superchain** stack, ensuring seamless asset routing between OP Mainnet, Base, and Lisk.
- **🛡️ Infrastructure Hardening:** Running critical blockchain infrastructure on a low-power **Armbian STB cluster**, secured behind **Cloudflare Tunnels** to ensure high availability without exposing public IPs.
- **📊 Production-Grade Relayers:** Moving from simple polling to **Event-Driven Architectures** capable of handling RPC latency, Chain Reorgs, and nonce management automatically.
- **🤖 Automated DevOps:** Managing CI/CD pipelines and Docker container health checks to ensure 99.9% uptime for bridge relayers.

---

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=faqihudin703&theme=react-dark&hide_border=true&area=true&radius=16" width="100%" alt="Contribution Graph" />
  <br>
  
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=faqihudin703&layout=compact&theme=radical" alt="Top Langs" width="100%" />
</p>
