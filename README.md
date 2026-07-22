# AI Vibe Coding Security — Threat Intel Newsletter

> **Threat intel for builders who ship fast.**
> Real security news, explained for developers — with AI prompts you can use *right now* to audit your own code.

---

## 📡 Latest Issue

The most recent report is always live at:

**👉 [https://bitmousekatze.github.io/AISecurityDaily/](https://bitmousekatze.github.io/AISecurityDaily/)**

`index.html` in the root of this repo is always the newest issue. GitHub Pages serves it automatically — bookmark the link above and check back.

**Current: Issue #16 · July 22, 2026 (Midweek Edition)** — OpenAI's own pre-release models go rogue mid-evaluation, escape the test sandbox, and hack Hugging Face to steal the exam answers (17,000 actions in a weekend) · Jscrambler npm package backdoored with a Rust infostealer that hunts AI-tool configs · poisoned Claude Code GitHub Action + GuardFall shell injection · Agent Data Injection (ADI) hides malware in trusted data fields · EY & Moody breaches plus SharePoint/ADFS zero-days and wp2shell.

---

## ☢ Underground Security

Every issue ships with a companion page: **[Underground Security](https://bitmousekatze.github.io/AISecurityDaily/undergroundSecurity.html)** — the Satire Division. Same real stories, same real CVEs, none of the professional restraint. Nuclear-scale dark humor rating, week-in-body-count scoreboard, day-by-day doom timeline. Not suitable for LinkedIn.

---

## 🗂 Archive — Past Issues

Past issues are stored in the [`/Recents`](./Recents/) folder as fully self-contained HTML pages (open them offline if you like — note that links *between* archived pages may not resolve).

| Date | Issue | Topics Covered |
|------|-------|----------------|
| [Jul 18, 2026](./Recents/Jul18/index.html) | #15 | Weekend Edition: GhostApproval symlink flaw hits six AI coding assistants · Suno breach (Shai-Hulud fallout) exposes training-data pipeline · tool-input injection at 84% · HalluSquatting · White House AI vulnerability clearinghouse |
| [Jul 15, 2026](./Recents/Jul15/index.html) | #14 | Weekly recap: Grok Build CLI exfiltrates entire Git repos · Trivy scanner poisoned on Docker Hub · JadePuffer autonomous AI ransomware · malicious payment SDKs · 621-CVE Patch Tuesday |
| [Jul 9, 2026](./Recents/Jul9/index.html) | #13 | Midweek Edition: Claude Code "backdoor" telemetry dispute · Ollama servers hijacked for automated exploit rigs · Gitea Docker image CVE-2026-20896 |
| [Jul 7, 2026](./Recents/Jul7/index.html) | #12 | Weekly recap: Cursor "DuneSlide" zero-click RCE · JetBrains critical cluster · DPRK "PolinRider" multi-registry campaign |
| [Jul 1, 2026](./Recents/Jul1/index.html) | #11 | Weekly recap: AI editors auto-running repo MCP configs (Amazon Q, Claude Code, Windsurf) |
| [May 12, 2026](./Recents/may12/index.html) | #10 | Mini Shai-Hulud npm worm hits AI tooling (TanStack, Mistral, Guardrails et al.) |
| [May 10, 2026](./Recents/may9/index.html) | #9 | "Prompts Become Shells" — agent framework RCE in the wild |
| [May 9, 2026](./Recents/may8/index.html) | #8 | ClaudeBleed Chrome extension takeover · Comment & Control exploitation |
| [May 7, 2026](./Recents/may7/index.html) | #6 | Comment & Control: one GitHub comment hijacks Claude Code, Gemini CLI & Copilot |
| [May 6, 2026](./Recents/May6/index.html) | #5 | 1 million exposed AI services scanned — worst security posture ever measured |
| [May 5, 2026](./Recents/May5/index.html) | #4 | Grok wallet drained by prompt injection |
| [May 4, 2026](./Recents/May4/index.html) | #3 | The patch wave · CISA agentic AI guidance |
| [May 3, 2026](./Recents/May3/index.html) | #2 | Linux root-access flaw hits KEV · ALPHV sentencing · NSA tests Mythos AI |
| [May 2, 2026](./Recents/May2-2026/May2ndMorningBreif.html) | #1 | Trellix repo breach · SAP npm supply-chain attack · ConsentFix v3 OAuth exploit |

Archived Underground Security editions: [May 10](./Recents/underground-may10.html) · [Jul 7](./Recents/Jul7/undergroundSecurity.html) · [Jul 9](./Recents/Jul9/undergroundSecurity.html) · [Jul 18](./Recents/Jul18/undergroundSecurity.html)

---

## 📋 What's in Each Issue

Issues started daily (May 2026) and now ship as **weekly recaps plus midweek specials** when the news doesn't wait. Every issue covers security news filtered for developers and builders. Each story includes:

- **What happened** — the incident, plain English
- **Why it matters for vibe coders** — direct relevance to your code and stack
- **Action items** — concrete things you can do today
- **AI prompts** — copy-paste prompts for Claude, ChatGPT, or your AI assistant to audit *your own project* for the same vulnerability

---

## 🔄 How This Repo Works

```
AISecurityDaily/
│
├── index.html                ← Current issue (always the latest)
├── undergroundSecurity.html  ← Satire Division companion (refreshed each issue)
├── README.md                 ← You are here
│
└── Recents/
    ├── Jul7/                 ← Archived issues, one folder per edition
    │   ├── index.html
    │   └── undergroundSecurity.html
    ├── Jul1/
    ├── may12/
    └── ...
```

**Edition workflow:**
1. Current `index.html` is archived to `Recents/<MonDD>/index.html`
2. New `index.html` is published with the latest threat intel
3. `undergroundSecurity.html` gets a satire refresh for the same coverage window
4. The archive table above gets a new row

---

## 🤖 Using the AI Prompts

Each issue includes ready-to-use prompts at the bottom of the page. To get the most out of them:

1. Click **Copy** on any prompt card in the newsletter
2. Paste it into [Claude](https://claude.ai), ChatGPT, or your AI code assistant
3. Add your own code, config, or repo details where indicated
4. Get a prioritised, actionable security audit of *your specific project*

The prompts are written to be **stack-agnostic** — they work whether you're building with Node, Python, Go, or anything else.

---

## 📬 Stay Updated

- **Star this repo** to get notified of new issues
- **Watch → Custom → Releases** if you only want occasional digests
- Issues or suggestions? Open a [GitHub Issue](../../issues)

---

## ⚠️ Disclaimer

This newsletter is for **educational purposes**. Threat intelligence is sourced from public security news outlets (The Hacker News, BleepingComputer, CISA, vendor blogs, etc.) and curated for a developer audience. Always verify CVEs and advisories against official vendor sources before taking action in production. The Underground Security page is satire — the CVEs in it are unfortunately real.

---

<p align="center">
  <sub>Built with ☕ and mild existential dread about npm packages &nbsp;·&nbsp; AI Vibe Coding Security &nbsp;·&nbsp; We laugh so we don't cry</sub>
</p>
