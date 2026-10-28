<h1 align="center">Hi, I'm Alejandro 👋</h1>

<p align="center">
  ⚡ <b>Web3 × AI Engineer</b> &nbsp;·&nbsp; 🔨 Shipping on Solana, EVM (Ethereum · Base) & Starknet &nbsp;·&nbsp; 📍 Panamá 🇵🇦
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/Anchor-512DA8?style=flat-square&logo=solana&logoColor=white" alt="Anchor" />
  <img src="https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white" alt="Solana" />
  <img src="https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white" alt="Solidity" />
  <img src="https://img.shields.io/badge/Foundry-1C1C1C?style=flat-square&logo=ethereum&logoColor=white" alt="Foundry" />
  <img src="https://img.shields.io/badge/Cairo-EC796B?style=flat-square&logo=starknet&logoColor=white" alt="Cairo" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/wagmi%20%2F%20viem-1C1B1F?style=flat-square&logo=ethereum&logoColor=white" alt="wagmi/viem" />
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code" />
</p>

---

I build smart contracts and the apps around them: **Rust + Anchor on Solana**,
**Solidity on Ethereum and Base**, and **Cairo on Starknet**.

I work with **Claude Code as an engineering partner**, under manual approval. I set the
design and decide what each test has to prove, and I verify every important test by
breaking the code on purpose and watching it go red.

This profile is my working portfolio. Every repo here is real work, and each README
documents the decisions, the bugs I found, and the known limitations, not only what works.

- 🦀 Shipping on **Solana**: Anchor programs, property-based tests, live on-chain data
- 🎓 Studied **Blockchain Engineering & AI** at CodeCrypto (2026), still shipping the remaining projects
- 📚 **8 Anthropic Academy courses**: Claude, Claude Code, agent skills, subagents, MCP
- 💬 Open to remote Smart Contract / Protocol / Web3 roles (LATAM & global)

---

## 🚀 Featured Projects

### 🚨 [solana-rug-radar](https://github.com/alebeta06/solana-rug-radar)
Real-time rug-pull detector on live **Solana mainnet** data. Two rules calibrated against
17 million events from a full night of mainnet: the red one reached **97.9 % precision**,
shown per rule, never averaged. The README documents the signals the data ruled out and
what the detector cannot see. Runs with `docker compose up`, no API key needed: it replays
a real recorded hour of mainnet.

`TypeScript` · `Node.js` · `Docker` · `242 tests` · `CI`

🎥 [Video](https://www.youtube.com/watch?v=eeqsJjTLrds)

### 🔁 [solana-token-swap](https://github.com/alebeta06/solana-token-swap)
Fixed-price SPL token swap in **Rust + Anchor 1.2**, deployed on **devnet**. PDA vaults,
canonical mint order, decimals read from the `Mint` instead of trusted from the caller.
Property-based tests (500,000 generated cases) found a real panic that 27 integration
tests could not see. 133 tests across three suites, CI verified by sabotage.

`Rust` · `Anchor` · `TypeScript` · `Next.js`

🔗 [Live Demo](https://solana-token-swap.vercel.app/) · 🎥 [Video](https://www.youtube.com/watch?v=nUb5637SPXo)

### 🗃️ [northwind-fullstack](https://github.com/alebeta06/northwind-fullstack)
REST API in **Rust + Rocket** over SQLite, with a Next.js admin panel. Full CRUD over the
Northwind database: thread-safe connection the compiler demands, foreign keys enforced and
shown as a business rule (409), and a cold-start-aware UI for a free-tier backend.
15 tests, clippy clean with `-D warnings`.

`Rust` · `Rocket` · `SQLite` · `Docker` · `Next.js 15`

🔗 [Live Demo](https://northwind-fullstack.vercel.app) · 🎥 [Video](https://www.youtube.com/watch?v=KIrc3B_cqvE)

### 🦊 [chrome-wallet](https://github.com/alebeta06/chrome-wallet)
Ethereum wallet as a **Chrome extension (Manifest V3)**, built from scratch: BIP-39/44,
EIP-1193, EIP-6963 and EIP-712, per-origin permissions. Keys live only in the service
worker, and the build fails if crypto code becomes reachable from the UI.
37/37 specs · 933 unit tests + 22 end-to-end tests with Playwright.

`TypeScript` · `React 19` · `ethers v6` · `Playwright`

🔗 [Live dApp](https://chrome-wallet.vercel.app) · 🎥 [Video](https://www.youtube.com/watch?v=klAlTtGQTpw)

### 🤝 [Escrow-DApp](https://github.com/alebeta06/Escrow-DApp)
Non-custodial escrow for **atomic ERC20 swaps** between two parties who don't trust each
other: either both legs of the swap settle, or neither does. CEI pushed down to the file
layout: libraries own the *effects*, the contract owns the *checks* and *interactions*.
Live on **Ethereum Sepolia** with verified contracts · 32 Foundry tests (100% coverage on
core contracts) + 6 Playwright E2E tests against a real chain.

`Solidity 0.8.28` · `Foundry` · `Next.js 15` · `ethers v6`

🔗 [Live Demo](https://escrow-d-app-omega.vercel.app) · 🎥 [Video](https://www.youtube.com/watch?v=A6CcRPFZaFY) · 🔍 [Verified contract](https://sepolia.etherscan.io/address/0x426F0B446139098D1CAc0883474b7B53c40F285A#code)

### 🛒 [ecommerce-web3](https://github.com/alebeta06/ecommerce-web3)
Multi-vendor Web3 marketplace on Ethereum Sepolia: buy a EUR-pegged stablecoin (EURT) with
a real card via Stripe, then spend it on-chain. Solidity + Foundry contracts, 4 Next.js
apps, atomic multi-seller checkout.

`Solidity` · `Next.js` · `TypeScript`

🔗 [Live Demo](https://ecommerce-web3-web-customer.vercel.app/) · 🎥 [Video](https://www.youtube.com/watch?v=MqFWcHYnJ5o)

---

## 📦 More Projects

- 💰 **[btc_lending_project](https://github.com/alebeta06/btc_lending_project)**: decentralized lending protocol on **Starknet** · `Cairo` · [Demo](https://btc-lending-project.vercel.app/) · [Video](https://www.youtube.com/watch?v=MeWbsV4b8xE)
- 🗳️ **[DaoVotacionGasless](https://github.com/alebeta06/DaoVotacionGasless)**: gasless DAO voting with meta-transactions (EIP-2771), members don't pay gas · `Solidity` · `Foundry` · [Video](https://www.youtube.com/watch?v=0Yt6Gab3BtY)
- 📄 **[documentSignStorage](https://github.com/alebeta06/documentSignStorage)**: store and verify document signatures on Ethereum · `Solidity` · `Next.js` · [Demo](https://document-sign-storage.vercel.app/) · [Video](https://www.youtube.com/watch?v=JViYTTo-3Vg)
- 💧 **[DAG_Yield_Aggregator](https://github.com/alebeta06/DAG_Yield_Aggregator)**: my first hackathon (ETH Canal). Yearn-style yield aggregator MVP: vault, controller and a simulated strategy with `harvest()` and `rebalance()`, on BlockDAG testnet · `Solidity` · `Foundry` · `Scaffold-ETH 2` · [Demo](https://mydex-alebeta06s-projects.vercel.app/)

---

## 🛡️ Security Work

Smart contract security is my main focus now, practicing on CodeHawks First Flights. I still take on Solana, Starknet and Ethereum bounties when they come up:

- **[codehawks-security-portfolio](https://github.com/alebeta06/codehawks-security-portfolio)**: Puppy Raffle practice audit (First Flight #1). 3 High, 1 Medium and 3 Low, each with a written report, and Foundry PoCs for the Highs and the Medium: reentrancy in `refund()`, weak randomness in `selectWinner()`, `totalFees` truncation and a DoS in `enterRaffle()`. Next: Thunder Loan
- **[cairo-audit-skill](https://github.com/alebeta06/cairo-audit-skill)**: open-source Agent Skill for AI-assisted Cairo audits
- In my own code: bugs found by property tests, every test checked by sabotage, and known limitations written down instead of hidden

---

## 🤝 Connect

<p align="center">
  <a href="https://linkedin.com/in/alebeta"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://x.com/Ale_Beta"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" /></a>
  <a href="https://youtube.com/@alebeta06"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" /></a>
</p>

<p align="center"><i>"From smart contract to AI agent — one shipped project at a time."</i></p>
