<h1 align="center">🤖 aptratcn</h1>
<p align="center"><b>Security-First Agent Skills</b></p>
<p align="center">Zero-dependency markdown skills for Claude Code, Cursor, OpenClaw, and any AI agent.</p>
<p align="center"><b>Don't install blind. Guard before you trust.</b></p>

---

## 🔒 Core Skills

| Repo | Description |
|------|-------------|
| [**Skill Audit**](https://github.com/aptratcn/skill-audit) | Pre-install security scanner. 7.5% of skills are malicious — audit first |
| [**Install Guard**](https://github.com/aptratcn/skill-install-guard) | 🆕 Pre-install security for npm/pip. Typosquat + supply chain detection |
| [**Hermes Billing Guard**](https://github.com/aptratcn/skill-hermes-billing-guard) | Detect silent billing routing bugs in Claude Code (HN 984pts) |
| [**Prompt Guard**](https://github.com/aptratcn/prompt-guard) | Detect & resist prompt injection attacks. 4-layer defense |
| [**MCP Security Audit**](https://github.com/aptratcn/skill-mcp-security-audit) | Audit MCP servers before trusting them |
| [**Model Router**](https://github.com/aptratcn/skill-model-router) | Smart model selection. Route tasks to the right tier, slash costs 70% |
| [**Token Optimizer**](https://github.com/aptratcn/skill-token-optimizer) | Reduce AI agent token consumption by 98%. Lazy loading + compression |
| [**Error Doctor**](https://github.com/aptratcn/error-doctor) | Systematic error recovery. Stop burning tokens on blind retries |
| [**Session Checkpoint**](https://github.com/aptratcn/session-checkpoint) | Save & restore agent context at critical moments |
| [**Agent Memory**](https://github.com/aptratcn/skill-agent-memory) | Unified memory layer. Auto-persist, semantic search, cross-session recall |

---

## 📊 Why These Skills Matter

**The numbers:**
- **7.5% of 14,706 skills are malicious** (RankClaw audit, 2026)
- **59 critical-risk droppers** found disguised as legitimate tools (Vett.sh)
- **PyTorch Lightning compromised** via malicious dependency (Apr 2026)

**What malicious installs can do:**
- 🔓 Leak your API keys (OpenAI, Anthropic, AWS, Stripe)
- 💀 Execute arbitrary commands on your machine
- 📤 Exfiltrate your source code
- 🔄 Establish persistent backdoors

---

## 🛡️ Defense Stack

```
Package install → Install Guard → (pass) → Install → Prompt Guard (runtime)
                   ↓
                   (fail) → 🚫 Block
```

| Layer | Tool | Protects Against |
|-------|------|-----------------|
| **Package install** | [skill-install-guard](https://github.com/aptratcn/skill-install-guard) | Typosquat + supply chain |
| **Skill install** | [skill-audit](https://github.com/aptratcn/skill-audit) | Malicious skills |
| **MCP connect** | [skill-mcp-security-audit](https://github.com/aptratcn/skill-mcp-security-audit) | Malicious MCP servers |
| **Runtime** | [prompt-guard](https://github.com/aptratcn/prompt-guard) | Prompt injection |
| **Billing** | [skill-hermes-billing-guard](https://github.com/aptratcn/skill-hermes-billing-guard) | Hidden charges |

---

## 🔥 Trending Insights (May 2026)

GitHub trending + HN proves practical tools win:
- `mattpocock/skills` — **49,600+ stars, +6,187 today**. Small composable skills > big frameworks
- `free-claude-code` — 19,200+ stars. Cost control is the #1 pain point
- `GenericAgent` — 8,493 stars. Token efficiency = 6x less consumption
- `opensre` — 4,080 stars. AI agents for incident response
- HN 961pts: Claude Code billing bug when commits mention competitors

**Our focus:** Security foundations + cost control that actually work.

---

<p align="center"><b>Zero dependencies • Pure markdown • MIT licensed</b></p>

<p align="center">
<a href="https://github.com/aptratcn/skill-audit">🔍 Skill Audit</a> •
<a href="https://github.com/aptratcn/skill-install-guard">🛡️ Install Guard</a> •
<a href="https://github.com/aptratcn/prompt-guard">🚫 Prompt Guard</a> •
<a href="https://github.com/aptratcn/skill-hermes-billing-guard">💰 Billing Guard</a>
</p>
