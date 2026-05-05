# 👋🏾 Hey, I'm Z! Web3 Security Researcher & Smart Contract Auditor

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-FC8C03?style=for-the-badge)
![Code4rena](https://img.shields.io/badge/Code4rena-181717?style=for-the-badge)
![Sherlock](https://img.shields.io/badge/Sherlock-003366?style=for-the-badge)
![Etherscan](https://img.shields.io/badge/Etherscan-1C1C1C?style=for-the-badge)
![Security%20Research](https://img.shields.io/badge/Security_Research-0D1117?style=for-the-badge&logo=hackaday)

---

Aspiring smart contract auditor building DeFi security expertise through deep protocol analysis. Focused on EVM security, Solidity analysis, and precision math. 2 valid High findings on Code4rena. Currently: Day 21/90 of intensive audit preparation

---

## ⚡ Highlights

- 🧩 **2 High-Severity Valid Findings (Rewarded)** - Code4rena (Forte Float128)
- 🧱 **1 Valid Finding** - Sherlock (Crestal Network, duplicate)
- ❌ **1 Invalid / Intended Behavior Report** - documented for learning transparency
- 🧪 Foundry-based test + PoC workflow  
- 🧰 Tools: Foundry · Slither · Aderyn · Anvil · Echidna · Remix · Etherscan

---

## 🎯 Current Focus (May 2026)

**Protocol Deep-Dives:** Building security pattern recognition through line-by-line analysis
- ✅ Uniswap V2 (AMM mechanics, K invariant, reentrancy patterns)
- 🔄 Aave V3 (lending, liquidations, health factors)
- 📋 Next: Compound, Curve, Lido

**Contest Strategy:** Selective participation when protocols align with studied patterns

📊 Progress: Day 21/90 of intensive preparation

---

## 🔬 Featured Work

### Uniswap V2 Security Analysis
Deep-dive into `swap()`, `mint()`, `burn()` with security pattern analysis and architecture diagrams.

**Key insights:**
- Lock modifier prevents reentrancy across all state changes
- Balance-based calculations prevent spoofing attacks
- `MINIMUM_LIQUIDITY` burn prevents donation attacks
- $\Large {k}$ invariant ensures pool integrity

[Read Full Analysis →](https://github.com/z0ls3c/uniswap-v2-security-analysis)

**Published:** [Twitter Thread](https://x.com/z0ls3c/status/2051265488072618026?s=20) | 790-line analysis

---

## 📂 Audit Portfolio

| Finding | Platform | Severity | Status | Link |
|----------|-----------|-----------|--------|------|
| `Float128::toPackedFloat` Fails to Promote to L Size When Exponent Is Critically Low | Code4rena – Forte | High | ✅ **Valid (Rewarded)** | [View Report](https://github.com/z0Ld3v/z0L-audits/blob/main/audit-contests/Code4rena/2025-04-forte-float128-solidity-library/finding1.md) |
| `Ln::ln()` Fails to Validate Negative Inputs, Causing Division-by-Zero Panics | Code4rena – Forte | High | ✅ **Valid (Rewarded)** | [View Report](https://github.com/z0Ld3v/z0L-audits/blob/main/audit-contests/Code4rena/2025-04-forte-float128-solidity-library/finding2.md) |
| Unauthorized Token Transfer via Insufficient Access Control | Sherlock – Crestal Network | Medium | ⚠️ **Valid (No Reward)** | [View Report](https://github.com/z0Ld3v/z0L-audits/blob/main/audit-contests/Sherlock/2025-03-crestal-network/unauthorized-token-transfer.md) |
| Reward Manipulation in Referral Logic | Code4rena – Nudge | – | ❌ **Invalid (Intended Behavior)** | [View Report](https://github.com/z0Ld3v/z0L-audits/blob/main/practice-audits/false-positives/code4rena/2025-03-nudge/rewardmanipulation.md) |

👉 See full portfolio: [**z0L-audits**](https://github.com/z0Ld3v/z0L-audits)

---

## 🧠 Audit Workflow

1. **Recon & Architecture Mapping**: Identify trust boundaries and actor roles  
2. **Static Review**: Analyze state transitions and access modifiers  
3. **Dynamic Testing**: Foundry fuzz + invariant testing, mainnet forks  
4. **Exploit Simulation**: Model realistic attack paths  
5. **Impact Analysis**: Evaluate severity, risk exposure, and cascading effects  
6. **Reporting**: Clear PoC, rationale, mitigation, and lessons learned  

---

## 🧰 Tech Stack

| Domain | Tools / Frameworks |
|--------|--------------------|
| Security & Auditing | Foundry · Slither · Aderyn · Anvil · Echidna |
| Languages | Solidity · TypeScript |
| Analysis | Etherscan · Tenderly · Remix |
| Documentation | Markdown · Obsidian |

---

## 🗺️ Protocol Study Roadmap

Building audit expertise through systematic protocol analysis:

**Tier 1: Core DeFi Primitives (May - Oct 2026)**
1. ✅ Uniswap V2 (Constant Product AMM)
2. 🔄 Aave V3 (Lending & Liquidations)
3. Compound V2 (Simpler Lending - Comparison Study)
4. MakerDAO (CDP Mechanics & Oracles)
5. Curve (StableSwap Invariant)
6. Lido (Liquid Staking)

**Tier 2: Advanced Patterns (2027)**
- Uniswap V3/V4 (Concentrated Liquidity & Hooks)
- GMX V2 (Perpetuals)
- Synthetix (Derivatives)

Each deep-dive includes: architecture diagrams, security pattern analysis, attack vectors, and Foundry PoCs.

---

## 📈 Goals for 2026

**By July 2026:**

- ✅ Deep-dive 6 core DeFi protocols (Uniswap, Aave, Compound, Maker, Curve, Lido)
- ✅ Participate in 5+ high-quality audit contests (selective focus)
- ✅ Study 3+ major DeFi exploits with working PoCs
- ✅ Active Twitter presence sharing learnings

**By December 2026:**
- 🎯 Land junior auditor role or apprenticeship
- 🎯 Published technical write-ups on AMM & lending security
- 🎯 Contribute to open-source audit tooling

---

## 🧩 Philosophy

> “Precision is security.”  
> — z0L

I believe secure code is the byproduct of *clarity*, not just caution.  
Every function should explain why it’s safe, not just assume it.

---

## 📬 Connect

- **Twitter/X:** [@z0Ls3c](https://x.com/z0Ls3c)
- **Email:** <a href="mailto:z0ls3c@proton.me">Proton</a>  

---

🛡️ *Always learning. Always breaking (ethically). Always improving.*
