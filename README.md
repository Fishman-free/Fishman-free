<div align="center">

# 👋 Hi, I'm Fishman (Jude Ma · 马珠淇)

**🎓 CS Undergraduate · School of Information · Renmin University of China**

*Building intelligent agents at the intersection of AI, blockchain & autonomous systems.*

</div>

---

## 🚀 Flagship Projects

### 🛡️ AgentTrust · Trust Infrastructure for AI Agents
> [agenttrust.site](https://agenttrust.site) · Solidity · Next.js · Base Sepolia

Trust infrastructure for **agent-to-agent commerce**: identity registration (`AgentRegistry`), transaction escrow (`GuaranteeEscrow`), Schelling-point dispute arbitration (`SchellingVoting`), and immutable reputation records (`ReputationHub`) — aligned with **ERC-8004 (Trustless Agents)**. Four core contracts deployed and RPC-validated on Base Sepolia, backed by **183 Foundry tests** (unit / fuzz / E2E / invariant).

### 🔬 Poliscope · Multi-Agent Deep Research
> [poliscope.tech](https://poliscope.tech/) · Python · TypeScript

A **deep-research agent** for contested questions: seven specialized AI scientists gather evidence independently, cross-examine each other, and produce a controversy evidence map — every claim traces to its source, conclusions sit beside limitations, and dissent is preserved as named certificates instead of being voted away. Built on **EpistemoBrain**, the multi-agent generalization of MemoBrain (ACL Findings 2026). Web / API / CLI / Agent-Skill, four entrances to one protocol.

### 🥊 REDTEAM · Adversarial Security Research for AI Payment Agents
> Python · Ethereum · Active research

Studies how AI agents that read orders, call tools, and request payments hold the line on **user authorization**. Controlled attacks (merchant dialogue, tool returns, external docs, external memory) against L0/L1 payment permissions, paired attack/normal runs, independent verdicts on four separate records, defense-pack fixes that only pass a **pre-committed acceptance gate** — all under simulated funds. Includes a soulbound **Flower NFT** prototype (ERC-721 + ERC-5192, transfer permanently disabled) for audited research-contribution recognition.

### 📈 youngmoney (bnbot) · Quant Trading Framework
> Python · Paper-first

Binance USDT-M **mid/low-frequency** framework: trend breakout + time-series momentum + funding-rate carry, with hard risk controls (leverage caps, daily-loss circuit breaker, drawdown throttle, kill switch) and **walk-forward** backtesting. Current OOS segment (2026, fee-adjusted): +22.4% annualized, Sharpe 0.96, max drawdown −16.3% — stated honestly alongside its single-segment and post-hoc-tuning caveats.

### 🧠 DataMind · Conversational Data Analysis Platform
> Python · Flask · SSE

Upload data → auto-clean → quality scorecard → streaming Q&A → NL2Vis chart workbench → one-click reports. **Skill-first routing**: an LLM picks from 6 deterministic skills (stats / viz / trend / correlation / distribution / profile), evidence tables are computed by scripts before any explanation is generated — rules first, LLM explains, hallucination structurally excluded. POST-body SSE streaming, sandboxed code execution, 4-agent deep reports, graceful degradation everywhere. 338 unit tests.

### 🈶 Easy Translator · Hover-to-Translate
> [Edge Add-ons store](https://microsoftedge.microsoft.com/addons/detail/lnnglikclimokbdcgnpjelpigopdkjeb) · JavaScript

Hover an English word for ~5 seconds, get a card with Chinese definition, phonetics and examples. **Published on the Edge store**, plus a Windows desktop companion (Notepad / Word / WeChat — anywhere outside the browser). Built-in pdf.js reader for PDFs, local small-model engine (Ollama) for offline use, local vision-model OCR as the last-resort channel for text inside images. Strict gating: no recognized English word, no popup — ever.

---

## 🔬 Research

### 🧪 PINN + PhysicsHead · Physics-Informed Video Prediction
> PyTorch

**InkDrop**, a curated benchmark of 332 ink-diffusion-in-water clips with per-frame masks, plus a physics-informed training framework: a 125K-param **PhysicsHead** decodes the TAU backbone into concentration and velocity fields, supervised by advection–diffusion PDE residuals, Farnebäck optical-flow pseudo-labels, and mask constraints — present only during training, discarded at inference. Best config: **MSE −28.3%** vs TAU baseline (SSIM 0.942, PSNR 32.11 dB). PhysicsHead is packaged separately as a compact, removable auxiliary head.

---

## 🛠️ More Things I've Built

| Project | What it is |
|---|---|
| 🎭 **Human-Touch-Roundtable** | Self-hostable social-deduction game: humans and AI mixed at one table, three rounds + a debate + a reveal vote. TypeScript game core, Socket.IO sessions, SQLite persistence with crash recovery. |
| 🏛️ **RUCDAO** | Volunteer-service platform for Renmin University: PoV (Proof of Volunteer) contribution records, soulbound RUCOIN credence tokens, double-ended student/organizer flows. Compliance-first: no fiat peg, no transferability. |
| 📝 **PAPER-SKILL** | A Claude Code skill that turns CUMCM (China's national math-modeling contest) paper writing from intuition into discipline — judging criteria, red lines, abstract paradigms extracted from real winning papers, compliance checker, LaTeX template. `npx github:Fishman-free/PAPER-SKILL` |
| ⚡ **c-problem** | Complete reproducible pipeline for CUMCM 2026 Problem C (microgrid dispatch): sparse LP, mean–CVaR stochastic strategies, ablations, sensitivity, 16 vector figures, paper source. |
| ✒️ **jianzhen.skill** | A writing-perspective skill distilled from 8 first-hand interviews and 23 works of Taiwanese essayist 简媜 — mental models, decision heuristics, and expression DNA for "humid" prose. |

---

## 🏆 Competitions & Projects

- 🤖 **Platform Governance Agent** — national-level innovation project: cloud-collaborative AI agents for detecting GEO-poisoned webpages; I lead the agent-development module
- 🧬 **AI-CAR-NK Cell Drug** — Challenge Cup Shanghai, municipal 3rd prize: full-process intelligent QC for AI-CAR-NK immunotherapy
- 🏫 **AI × Metaverse Smart Campus** — Challenge Cup Beijing, municipal 2nd prize: UE5 digital humans + simulated campus environments
- 🥉 **MCM/ICM 2025** — Honorable Mention
- 📊 **CUMCM 2026** — complete solution & paper in [`c-problem`](https://github.com/Fishman-free/c-problem)

---

## 🧠 About Me

- 🧠 ENTJ | Builder mindset
- 🤖 AI agents & autonomous systems — how they reason, remember, and transact
- 🗣️ Deep discussions on politics, technology & society
- 📈 Quantitative investing & algorithmic strategies
- ⛓️ Blockchain, digital currencies & machine-native commerce
- 🥽 Metaverse & next-generation digital ecosystems
- 🎧 K-pop enjoyer
- 🏛️ Chinese politics & modern Chinese history
- 💻 Vibe coder turning ideas into working products

## 🛠️ Tech I Use

- **Languages:** Python · TypeScript/JavaScript · Solidity · C/C++
- **Domains:** AI Agents & LLM systems · Web3 / smart contracts · Quant trading · Full-stack web · Video prediction

---

## 📫 Contact Me

- 📧 Email: [2025201699@ruc.edu.cn](mailto:2025201699@ruc.edu.cn)
- 🐙 GitHub: you're already here

<div align="center">

*Most repos ship with honest status matrices — what is proven, what is assumed, and what is still missing.*

</div>
