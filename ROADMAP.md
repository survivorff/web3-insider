# Roadmap

Rolling plan for what gets written next. Event-driven — order shifts as news breaks.

**Status legend:** 🟢 drafting · 🟡 outlined · ⚪ planned · ✅ published

---

## 2026 Q2 — Foundations

门面首篇以 meme 交易为开仓,建立"宽、可深可浅、引流"的仓库调性。之后转向各个链上基础设施的深拆。

| # | Status | Title | Why now |
|---|--------|-------|---------|
| 01 | 🟢 | **Your $100 Meme Buy Costs $107. Here's Where the $7 Goes.** | 开仓首篇。反差标题 + 真实交易解剖 + 天然引流到 meme-trade-wiki。平台方视角独家,小白专业通吃。 |
| 02 | 🟡 | **Why Hyperliquid Won Perps: A CEX Engineer's Architectural Breakdown** | 70%+ 链上 perp 份额。HyperBFT + HyperCore + HyperEVM 是"链上 CLOB"问题最完整的答卷。 |
| 03 | ⚪ | **Jito's BAM: The End of Solana's Open Mempool** | Block Assembly Marketplace 2025 年 7 月上线,TEE 里的交易调度,重塑 Solana MEV 格局。 |
| 04 | ⚪ | **Firedancer on Mainnet: What Actually Changed** | Jump 的 C client 已上线,SIMD-0256 把 CU 推到 60M+。实际影响和大部分报道不一样。 |
| 05 | ⚪ | **Alpenglow: Solana's 150ms Finality, and What It Breaks** | Q3 2026 目标。替换 PoH + Tower BFT。对于所有假设 ~12 秒 finality 的基建,这是迁移不是免费升级。 |

---

## 2026 Q2/Q3 — Crypto × AI Infrastructure

This is where the next wave is being plumbed. Focus on the rails, not the hype.

| # | Status | Title | Why now |
|---|--------|-------|---------|
| 06 | ⚪ | **AWS Bedrock AgentCore Payments: Autonomous Agents Now Pay in Stablecoins** | Announced May 7, 2026, with Coinbase + Stripe. x402 rails. Cambrian reports $50M already flowing. This is the CEX-AI intersection I've been waiting for. |
| 07 | ⚪ | **EIP-7702 in Production: The Wallet Delegation Playbook (And Its Phishing Vector)** | Active since Pectra. Privy/Safe/Biconomy rolling it out. Fresh arXiv paper on the phishing surface. Real security implications for every exchange supporting deposits from smart EOAs. |
| 08 | ⚪ | **Stablecoin Payment Rails in 2026: Visa $7B, Meta Creators on USDC, and the Back-Office Problem Everyone Ignores** | Most coverage talks about "adoption." Almost none talks about reconciliation, FX pinning, KYT, and custody-vs-settlement separation — the parts that kill payment integrations inside exchanges. |

---

## 2026 Q3+ — Post-Mortems & Insider Views

Content only someone who's shipped production trading systems can write well.

| # | Status | Title | Angle |
|---|--------|-------|-------|
| 09 | ⚪ | **The JELLY Incident Revisited: What Every Perp DEX Should Learn About HLP Vaults** | One year on. What Hyperliquid fixed, what still isn't fixed, and what this teaches anyone building an on-chain perp. |
| 10 | ⚪ | **What Happens Inside a CEX When a New Token Gets Listed** | From proposal to hot/cold wallet provisioning to oracle integration. The workflow is nothing like what outsiders imagine. |
| 11 | ⚪ | **When Solana Degrades: How Centralized Exchanges Actually Respond** | Congestion, partial fills, deposit freezes, support volume. The playbook. |
| 12 | ⚪ | **Integrating a Perp DEX as a CEX: The Hyperliquid / Aster / Drift Engineering Checklist** | From market data ingestion to hedge book management to user UX. |
| 13 | ⚪ | **KYT in Practice: What Chainalysis and TRM Actually Look Like Inside an Exchange** | Not the marketing version. The operational version. |

---

## Rules for this roadmap

- **No filler.** If an item can't clear the "does a peer actually want to read this" bar, it gets cut, not downgraded.
- **Event-driven insertions are fine.** If something big ships, it jumps the line.
- **Every published article must deliver at least one insight that isn't already in the top 10 Google results** for its topic. Otherwise, it doesn't ship.
- **Diagrams where they earn their place.** Prose for the argument, diagrams for state transitions, data flows, and architecture. No screenshots-as-content.

Feedback on priority is welcome — open an issue.
