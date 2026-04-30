<h1 align="center">🤖 aptratcn</h1>
<p align="center"><b>Security-First Agent Skills</b></p>
<p align="center">Zero-dependency markdown skills for Claude Code, Cursor, OpenClaw, and any AI agent.</p>
<p align="center"><b>Don't install blind. Audit before you trust.</b></p>

---

## 🔒 Core Skills

| Repo | Stars | Description |
|------|-------|-------------|
| [**Skill Audit**](https://github.com/aptratcn/skill-audit) | 1⭐ | Pre-install security scanner. 7.5% of skills are malicious — audit first |
| [**Prompt Guard**](https://github.com/aptratcn/prompt-guard) | 1⭐ | Detect & resist prompt injection attacks. 4-layer defense |
| [**Cognitive Debt Guard**](https://github.com/aptratcn/cognitive-debt-guard) | 1⭐ | Prevent the 23.5% incident spike from AI-generated code |
| [**Error Recovery**](https://github.com/aptratcn/skill-error-recovery) | 1⭐ | 4R framework: Recognize → Respond → Resolve → Reflect |
| [**MCP Security Audit**](https://github.com/aptratcn/skill-mcp-security-audit) | | Audit MCP servers before trusting them. Bitwarden CLI was compromised — your MCP could be next |
| [**Model Router**](https://github.com/aptratcn/skill-model-router) | | Smart model selection. Route tasks to the right tier, slash costs 70% |
| [**EVR Framework**](https://github.com/aptratcn/evr-framework) | | Execute-Verify-Report. Stop fake completions |

---

## 📊 Why These Skills Matter

**The numbers:**
- **7.5% of 14,706 skills are malicious** (RankClaw audit, 2026)
- **59 critical-risk droppers** found disguised as legitimate tools (Vett.sh)
- **Bitwarden CLI compromised via npm** — MCP servers have the same supply chain risks

**What malicious skills can do:**
- 🔓 Leak your API keys (OpenAI, Anthropic, AWS, Stripe)
- 💀 Execute arbitrary commands on your machine
- 📤 Exfiltrate your source code
- 🔄 Establish persistent backdoors

---

## 🛡️ Defense Stack

```
Third-party skill → Skill Audit → (pass) → Install → Prompt Guard (runtime)
                     ↓
                     (fail) → 🚫 Reject
```

| Layer | Tool | Protects Against |
|-------|------|-----------------|
| **Pre-install** | [skill-audit](https://github.com/aptratcn/skill-audit) | Malicious skills |
| **Runtime** | [prompt-guard](https://github.com/aptratcn/prompt-guard) | Prompt injection |
| **Code quality** | [cognitive-debt-guard](https://github.com/aptratcn/cognitive-debt-guard) | AI-generated bugs |
| **MCP** | [skill-mcp-security-audit](https://github.com/aptratcn/skill-mcp-security-audit) | Malicious MCP servers |
| **Errors** | [skill-error-recovery](https://github.com/aptratcn/skill-error-recovery) | Silent failures |

---

## 🔥 Trending Insights (May 2026)

GitHub trending proves practical security wins:
- `free-claude-code` (+16K stars) — Cost control is #1 pain point
- `mattpocock/skills` (+25K stars) — Small, composable skills dominate
- `context-mode` (+2.2K stars) — Token optimization = 98% savings

**Our focus:** Security foundations that matter.

---

<p align="center"><b>Zero dependencies • Pure markdown • MIT licensed</b></p>

<p align="center">
<a href="https://github.com/aptratcn/skill-audit">🔍 Skill Audit</a> •
<a href="https://github.com/aptratcn/prompt-guard">🛡️ Prompt Guard</a> •
<a href="https://github.com/aptratcn/skill-mcp-security-audit">🔒 MCP Audit</a>
</p>