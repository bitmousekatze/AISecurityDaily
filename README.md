# AI Vibe Coding Security — Daily Threat Intel Newsletter

![AI Vibe Coding Security](./assets/logo.jpg)

> **Threat intel for builders who ship fast.**
> Real security news, explained for developers — with AI prompts you can use *right now* to audit your own code.

---

## 📡 Latest Issue

The most recent report is always live at:

**👉 [https://bitmousekatze.github.io/AISecurityDaily/](https://bitmousekatze.github.io/AISecurityDaily/)**

`index.html` in the root of this repo is updated each day with the newest issue. GitHub Pages serves it automatically — just bookmark the link above and check back daily.

---

## 🗂 Archive — Recent Issues

Past issues are stored in the [`/Recent`](./Recent/) folder. Each file is a fully self-contained HTML page (no external dependencies) so you can open any of them offline too.

| Date | Issue | Topics Covered |
|------|-------|----------------|
| [May 2, 2026](./Recent/2026-05-02.html) | #001 | Trellix repo breach · SAP npm supply-chain attack · ConsentFix v3 OAuth exploit |

> New rows are added here each day when a previous issue is archived.

---

## 📋 What's in Each Issue

Every daily report covers the **last 12–24 hours** of security news filtered for developers and builders. Each story includes:

- **What happened** — the incident, plain English
- **Why it matters for builders** — direct relevance to your code and stack
- **Action items** — concrete things you can do today
- **AI prompts** — copy-paste prompts for Claude, ChatGPT, or your AI assistant to audit *your own project* for the same vulnerability

---

## 🔄 How This Repo Works

```
aivibe-security/
│
├── index.html          ← Today's issue (always the latest)
├── README.md           ← You are here
├── assets/
│   └── logo.jpg        ← Brand assets
│
└── Recent/
    ├── 2026-05-02.html ← Archived issues, one file per day
    ├── 2026-05-03.html
    └── ...
```

**Daily workflow:**
1. Current `index.html` is moved to `Recent/YYYY-MM-DD.html`
2. New `index.html` is published with the day's threat intel
3. The archive table above is updated with a link to the archived issue

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

- **Star this repo** to get notified of daily updates
- **Watch → Custom → Releases** if you only want weekly digests
- Issues or suggestions? Open a [GitHub Issue](../../issues)

---

## ⚠️ Disclaimer

This newsletter is for **educational purposes**. Threat intelligence is sourced from public security news outlets (The Hacker News, BleepingComputer, SecurityOnline, etc.) and curated for a developer audience. Always verify CVEs and advisories against official vendor sources before taking action in production.

---

<p align="center">
  <sub>Built with ☕ and mild existential dread about npm packages &nbsp;·&nbsp; AI Vibe Coding Security &nbsp;·&nbsp; Published daily</sub>
</p>
