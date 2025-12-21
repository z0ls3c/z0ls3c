# 👋 Hey, I'm Z — Web3 Security Researcher & Smart Contract Auditor

![Solidity](https://img.shields.io/badge/Solidity-363636?style=for-the-badge&logo=solidity&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-FC8C03?style=for-the-badge)
![Code4rena](https://img.shields.io/badge/Code4rena-181717?style=for-the-badge)
![Sherlock](https://img.shields.io/badge/Sherlock-003366?style=for-the-badge)
![Cantina](https://img.shields.io/badge/Cantina-0A0A0A?style=for-the-badge)
![Etherscan](https://img.shields.io/badge/Etherscan-1C1C1C?style=for-the-badge)
![Security%20Research](https://img.shields.io/badge/Security_Research-0D1117?style=for-the-badge&logo=hackaday)

---

I break and fix smart contracts.  
Focused on **EVM security**, **Solidity analysis**, and **precision math in DeFi systems**.  
Actively auditing, while developing PoCs and independent case studies.

---

## ⚡ Highlights

- 🧩 **2 High-Severity Valid Findings (Rewarded)** — Code4rena (Forte Float128)
- 🧱 **1 Valid Finding** — Sherlock (Crestal Network, duplicate)
- ❌ **1 Invalid / Intended Behavior Report** — documented for learning transparency
- 🧪 Foundry-based test + PoC workflow  
- 🧰 Tools: Foundry · Slither · Aderyn · Anvil · Echidna · Remix · Etherscan

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

1. **Recon & Architecture Mapping** — Identify trust boundaries and actor roles  
2. **Static Review** — Analyze state transitions and access modifiers  
3. **Dynamic Testing** — Foundry fuzz + invariant testing, mainnet forks  
4. **Exploit Simulation** — Model realistic attack paths  
5. **Impact Analysis** — Evaluate severity, risk exposure, and cascading effects  
6. **Reporting** — Clear PoC, rationale, mitigation, and lessons learned  

---

## 🧰 Tech Stack

| Domain | Tools / Frameworks |
|--------|--------------------|
| Security & Auditing | Foundry · Slither · Aderyn · Anvil · Echidna |
| Languages | Solidity · TypeScript · C |
| Analysis | Etherscan · Tenderly · Dune · Remix |
| Documentation | Markdown · Obsidian · Mermaid Diagrams |

---

## 📈 Goals for 2026

- 🕵🏽 Expand audit catalog with Cantina & Codehawks  
- ✍🏽 Publish monthly write-ups on logic & math vulnerabilities  
- 🧑🏽‍💻 Land a Web3 **Security Auditor / Smart Contract Engineer** role  
- 🔬 Contribute to open-source audit tooling

---

## 🧩 Philosophy

> “Precision is security.”  
> — z0L

I believe secure code is the byproduct of *clarity*, not just caution.  
Every function should explain why it’s safe, not just assume it.

---

## 📊 GitHub Stats

![z0Ld3v's GitHub stats](https://github-readme-stats.vercel.app/api?username=z0Ld3v&show_icons=true&theme=github_dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=z0Ld3v&layout=compact&theme=github_dark&hide_border=true)

---

## 📬 Connect

- **GitHub:** [z0Ld3v](https://github.com/z0Ld3v)
- **Twitter/X:** [@z0Ld3v](https://x.com/z0Ld3v)
- **Email:** <a href="mailto:z0ld3v@proton.me">Proton</a>  
- **Portfolio:** [z0L-audits](https://github.com/z0Ld3v/z0L-audits)

---

🛡️ *Always learning. Always breaking (ethically). Always improving.*
