<h1 align="center">Hi, I'm Alejandro 👋</h1>

<p align="center">
  ⚡ <b>Web3 × AI Engineer</b> &nbsp;·&nbsp; 🔨 Shipping on EVM (Ethereum · Base) & Starknet &nbsp;·&nbsp; 📍 Panamá 🇵🇦
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" alt="Solidity" />
  <img src="https://img.shields.io/badge/Cairo-EC796B?style=flat-square&logo=starknet&logoColor=white" alt="Cairo" />
  <img src="https://img.shields.io/badge/Foundry-1C1C1C?style=flat-square&logo=ethereum&logoColor=white" alt="Foundry" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/wagmi%20%2F%20viem-1C1B1F?style=flat-square&logo=ethereum&logoColor=white" alt="wagmi/viem" />
  <img src="https://img.shields.io/badge/MCP-000000?style=flat-square&logo=anthropic&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust (learning)" />
</p>

---

I build at the intersection of **smart contracts and AI agents** — writing and auditing
contracts on Ethereum, Base, and Starknet, and using **MCP + agentic workflows** to make
development and security reviews faster.

This profile is my working portfolio. Every repo here is real work, and I document the
technical lessons as I go — bugs I found and fixed, architecture decisions, and patterns I
learned shipping.

- 🔭 Currently completing a **Master's in Blockchain Systems & AI Engineering** (CodeCrypto)
- 🛡️ Building **open-source security tooling** for Cairo/Starknet (see `cairo-audit-skill` below)
- 🦀 Learning **Rust** → moving into **Solana** development next
- 🎓 **8× Anthropic certifications** — Claude, MCP & agentic workflows
- 💬 Open to remote Smart Contract / Protocol / Web3 Security roles (LATAM & global)

---

## 🚀 Featured Projects

### 🤝 [Escrow-DApp](https://github.com/alebeta06/Escrow-DApp)
Non-custodial escrow for **atomic ERC20 swaps** between two parties who don't trust each
other — either both legs of the swap settle, or neither does. CEI pushed down to the file
layout: libraries own the *effects*, the contract owns the *checks* and *interactions*.
Live on **Ethereum Sepolia** with verified contracts · 32 Foundry tests (100% coverage on
core contracts) + 6 Playwright E2E tests against a real chain.

`Solidity 0.8.28` · `Foundry` · `Next.js 15` · `ethers v6`

🔗 [Live Demo](https://escrow-d-app-omega.vercel.app) · 🎥 [Video](https://www.youtube.com/watch?v=A6CcRPFZaFY) · 🔍 [Verified contract](https://sepolia.etherscan.io/address/0x426F0B446139098D1CAc0883474b7B53c40F285A#code)

### 🛒 [ecommerce-web3](https://github.com/alebeta06/ecommerce-web3)
Multi-vendor Web3 marketplace on Ethereum Sepolia — buy a EUR-pegged stablecoin (EURT) with a real card via Stripe, then spend it on-chain. Solidity + Foundry contracts, 4 Next.js apps, atomic multi-seller checkout

`Solidity` · `Next.js` · `TypeScript`

🔗 [Live Demo](https://ecommerce-web3-web-customer.vercel.app/) · 🎥 [Video](https://www.youtube.com/watch?v=MqFWcHYnJ5o)

### 🗳️ [DaoVotacionGasless](https://github.com/alebeta06/DaoVotacionGasless)
Gasless DAO governance — members vote via **meta-transactions**, so they don't pay gas.
Production-ready.

`Solidity` · `Foundry`

🎥 [Video](https://www.youtube.com/watch?v=0Yt6Gab3BtY)

### 🛡️ [cairo-audit-skill](https://github.com/alebeta06/cairo-audit-skill)
Open-source **Anthropic Agent Skill** for AI-assisted security audits of Cairo smart
contracts on Starknet. MCP-powered; structures the audit workflow and surfaces known
vulnerability patterns. *(In active development — paused, resuming Jul–Aug 2026.)*

`Cairo` · `snforge` · `Caracal` · `MCP` · `Agent Skills`

### 💰 [btc_lending_project](https://github.com/alebeta06/btc_lending_project)
Decentralized lending protocol on **Starknet**.

`Cairo` · `TypeScript`

🔗 [Live Demo](https://btc-lending-project.vercel.app/) · 🎥 [Video](https://www.youtube.com/watch?v=MeWbsV4b8xE)

### 🔁 [DAG_Yield_Aggregator](https://github.com/alebeta06/DAG_Yield_Aggregator)
Decentralized exchange built for the **ETH Canal Hackathon**.

`Solidity` · `TypeScript`

🔗 [Live Demo](https://mydex-alebeta06s-projects.vercel.app/)

### 📄 [documentSignStorage](https://github.com/alebeta06/documentSignStorage)
On-chain document authenticity — store and verify document signatures on Ethereum.

`Solidity` · `Next.js` · `TypeScript`

🔗 [Live Demo](https://document-sign-storage.vercel.app/) · 🎥 [Video](https://www.youtube.com/watch?v=JViYTTo-3Vg)

---

## 🛡️ Security Work

Moving into smart contract security auditing. Current focus:

- **[CodeHawks](https://codehawks.cyfrin.io/)** — working through First Flights;
  findings published as I complete them
- **[cairo-audit-skill](https://github.com/alebeta06/cairo-audit-skill)** — open-source
  Agent Skill for AI-assisted Cairo audits *(resuming Jul–Aug 2026)*
- Audit-minded by default in my own code: strict CEI, custom errors, `SafeERC20`,
  100% coverage on core contracts

---

## 🤝 Connect

<p align="center">
  <a href="https://linkedin.com/in/alebeta"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/Ale_Beta"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://warpcast.com/alebeta06"><img src="https://img.shields.io/badge/Farcaster-855DCD?style=for-the-badge&logo=farcaster&logoColor=white" alt="Farcaster" /></a>
  <a href="https://youtube.com/@alebeta06"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
</p>

<p align="center"><i>"From smart contract to AI agent — one shipped project at a time."</i></p>
