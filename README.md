<p align="center">
  <a href="https://tandemloop.app">
    <img src="https://tandemloop.app/assets/images/logo.png" alt="TandemLoop logo" width="180">
  </a>
</p>

<h1 align="center">TandemLoop</h1>
<p align="center"><strong>Private, self‑hosted collaboration for small teams.</strong></p>
<p align="center">
  <a href="https://tandemloop.app">tandemloop.app</a> ·
  <a href="#-roadmap">Roadmap</a> ·
  <a href="#-getting-started">Getting started</a>
</p>

<p align="center">
  <a href="https://tandemloop.app"><img alt="Website" src="https://img.shields.io/badge/Website-tandemloop.app-2BA7FF"></a>
  <img alt="Status" src="https://img.shields.io/badge/Status-Private%20Alpha-3D3BEC">
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-37E1D6.svg"></a>
</p>

---

**TandemLoop** is a private, self‑hosted collaboration platform for small teams.  
It integrates chat, file sharing, tasks, and notes into a unified workspace — so you own your data, without bloated enterprise complexity.

## 🚀 Why TandemLoop?

- **Own your data** — Run on your own hardware, virtual machine, or cloud. No vendor lock‑in.  
- **Focus on collaboration** — Channels & DMs, file buckets, task cards, rich‑text notes. One tool, many workflows.  
- **Stay lightweight** — Minimal dependencies, streamlined UX, optimized for productivity.  
- **Modular and extensible** — Start simple, scale features (boards, sync, integrations) at your pace.

## 🎯 Target Use‑Cases

- Small teams (5–50 people) who need internal chat, shared files, task tracking and lightweight notes.  
- Projects or companies that prefer self‑hosting, strong data ownership, and limited external dependencies.  
- Teams that want a single platform (not piecing together dozens of tools) and still maintain flexibility.

## 🧩 Core Features (in development)

- **Channels & Direct Messages** — threaded replies, mentions, reactions.  
- **File Buckets** — drag‑and‑drop uploads, previews, passcode links for sharing.  
- **Tasks** — lightweight cards with owner, due date, status; quick creation via slash command.  
- **Notes** — rich‑text documents with inline attachments, slash commands, version history.  
- **Presence & Status** — know who’s online, set status messages, maintain privacy‑optimized presence.  
- **Keyboard Shortcuts & Quick Actions** — jump to channels, create tasks or notes in one keystroke.  
- **Themes** — dark mode by default, customizable accent colours.  
- **Smart Notifications** — mention alerts, per‑channel controls, minimal noise.

## 📁 Repo Layout

```
/
├─ website/                 # Static site for landing + docs/news
│  ├─ assets/css/root.css
│  ├─ assets/logo.png
│  ├─ index.html
│  ├─ features.html
│  └─ news.html
├─ server/                  # Self‑hosted EXE server (placeholder for now)
├─ clients/                 # Desktop/Mobile/Web clients (placeholder)
└─ .github/                 # CI and GitHub templates
```

## 🛠 Getting Started

### Preview the website locally
```bash
# From repo root
python3 -m http.server --directory website 8080
# or
npx serve website
```

> The self‑hosted server and clients are under active development. As these components land, setup scripts and docs will appear in `server/` and `clients/`.

## 🗺 Roadmap

- v0.1.0 – Private preview: channels, files, tasks, notes  
- v0.2.0 – Boards (kanban), filters, swimlanes  
- v1.0.0 – Stable public release: packaging (Docker), admin & roles, backups, integrations

## 📝 License

MIT — see [`LICENSE`](LICENSE).

---

<p align="center">
  <sub>© 2025 TandemLoop — Built for teams who want control without the bloat.</sub>
</p>
