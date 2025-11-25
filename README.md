# Hi there, I'm Faqihudin 👋

I'm an Informatics student transitioning into a **Blockchain Infrastructure Engineer**. I combine my strong background in network engineering and server automation to build resilient, decentralized systems. My focus has shifted from private labs to **architecting multi-chain interoperability protocols** and full-stack DeFi applications.

---

## 🛠️ Tech Stack & Core Competencies

<table>
  <tr>
    <td valign="top" width="50%">
      <strong>⛓️ Blockchain & Web3 Development</strong>
      <ul>
        <li><strong>Smart Contracts:</strong> Solidity, OpenZeppelin (Upgradeable/Proxy Pattern)</li>
        <li><strong>Frameworks:</strong> Hardhat, Ethers.js v6</li>
        <li><strong>Architecture:</strong> Cross-Chain Bridges (Lock-and-Mint), Hybrid Relayers</li>
        <li><strong>Frontend DApp:</strong> React.js, Vite, Tailwind CSS</li>
        <li><strong>Network Interaction:</strong> Public Testnets (Sepolia, Base, Hoodi)</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <strong>🔌 Infrastructure & DevOps</strong>
      <ul>
        <li><strong>Server Management:</strong> Linux (Ubuntu/Armbian), Docker & Compose</li>
        <li><strong>Networking:</strong> Advanced MikroTik (Mangle/QoS), Tailscale Mesh</li>
        <li><strong>Security:</strong> Cloudflare Tunnel (Zero Trust), UFW</li>
        <li><strong>Automation:</strong> Node.js (Long-running Services), Python, n8n</li>
        <li><strong>Observability:</strong> Grafana, Prometheus</li>
      </ul>
    </td>
  </tr>
</table>

---

## 🚀 Featured Project: Multi-Chain DeFi Ecosystem

I designed and deployed a live **Cross-Chain Bridge & DeFi Terminal** connecting **Sepolia**, **Hoodi**, and **Base** Testnets.

### 🏗️ Architecture Highlights:
- **Upgradeable Smart Contracts:** Implemented **Transparent Proxy Pattern** to manage protocol upgrades across multiple chains without changing contract addresses.
- **Hybrid Relayer Engine:** Engineered a custom Node.js relayer running on **Armbian (Dockerized)** that utilizes:
  - **Concurrency:** Non-blocking event listeners + polling backups.
  - **Fault Tolerance:** Idempotency checks to prevent double-spending.
  - **Data Safety:** "Deferred Flush" logic to protect SD Card lifespan while ensuring zero data loss during power outages (UPS backed).
- **Frontend Experience:** Built a responsive **React/Vite DApp** for Token Swaps (DEX), Liquidity Management, and Cross-Chain Bridging.

---

## 🔧 Ongoing Engineering & Research

- **🌉 V3 Multi-Chain Router:** successfully upgraded my bridge from a 1-to-1 model to a **1-to-N Router**, enabling dynamic asset routing between Sepolia, Hoodi, and Base Layer-2 using a single consistent contract address.
- **🛡️ Infrastructure Hardening:** Running critical blockchain infrastructure on a low-power **Armbian STB cluster**, secured behind **Cloudflare Tunnels** and monitored via **Tailscale**, ensuring high availability even without a static public IP.
- **📊 Real-World Simulation:** Moved away from private chains to **Public Testnets** to handle real-world challenges like gas management, chain reorganizations (reorgs), and RPC latency.
- **🤖 Automated DevOps:** Managing `systemd` services and Docker containers with health checks to ensure my Relayer and Node services maintain 99.9% uptime.

---

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=faqihudin703&theme=react-dark&hide_border=true&area=true&radius=16" width="100%" alt="Contribution Graph" />
  <br>
  
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=faqihudin703&layout=compact&theme=radical" alt="Top Langs" width="100%" />
</p>
