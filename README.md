<div align="center">

# 🎱 Soc Ops

### Social Bingo for In-Person Mixers

_Find people who match the clues. Get 5 in a row. Break the ice._

[![Play Now](https://img.shields.io/badge/▶%20Play%20Now-Live%20Demo-4f46e5?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![Lab Guide](https://img.shields.io/badge/📚%20Lab%20Guide-Workshop-0ea5e9?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)
[![Open in Codespaces](https://img.shields.io/badge/Open%20in-Codespaces-24292f?style=for-the-badge&logo=github)](https://codespaces.new/hugobarona/my-soc-ops-csharp-hb)

![.NET](https://img.shields.io/badge/.NET%2010-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor%20WASM-592BD4?style=flat-square&logo=blazor&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?style=flat-square&logo=github&logoColor=white)

</div>

---

## What is Soc Ops?

**Soc Ops** is a mobile-friendly Social Bingo game designed for team events, meetups, and conferences. Players roam the room, chat with others, and mark off squares when they find someone who fits the clue. First to get **5 in a row** wins!

It's a hands-on lab project built to showcase AI-assisted development with **GitHub Copilot** inside **VS Code** — using agents, context engineering, and multi-step automation to build a real app from scratch.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎲 **Randomized Board** | Every game generates a unique 5×5 bingo card from a pool of social questions |
| 💾 **Persistent State** | Game progress is saved to `localStorage` so you won't lose your card on reload |
| 🏆 **Win Detection** | Automatically highlights the winning row, column, or diagonal when you get 5 in a row |
| 📱 **Mobile-First** | Designed for phones — perfect for walking around a mixer |
| ⚡ **No Server Needed** | Runs entirely in the browser via Blazor WebAssembly |
| 🚀 **Auto-Deploy** | Pushes to GitHub Pages automatically on every merge to `main` |

---

## 🚀 Quick Start

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or higher

### Run Locally

```bash
cd SocOps
dotnet run
```

Then open your browser at `https://localhost:5001`.

### Build

```bash
cd SocOps
dotnet build
```

### Open in GitHub Codespaces

Get a fully configured dev environment in one click — no local setup required:

1. Click **Code** → **Codespaces** → **Create codespace on main**
2. Wait for the devcontainer to finish setup (~1 min)
3. Run the app:
   ```bash
   cd SocOps
   dotnet run
   ```

---

## 🗺️ Tech Stack

```
Blazor WebAssembly (.NET 10)   →  frontend & game logic
CSS utility classes             →  styling (custom Tailwind-like setup)
localStorage (JS interop)       →  game state persistence
GitHub Actions                  →  CI/CD
GitHub Pages                    →  hosting
```

---

## 📚 Workshop Lab Guide

This project is the foundation of a hands-on **GitHub Copilot Agent Lab**. Work through the steps to build and extend the game using AI-assisted development:

| Step | Title | What You'll Learn |
|------|-------|-------------------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Checklist | Lab goals and how to navigate |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup & Context Engineering | Copilot instructions, `.github/` config |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend | Build the UI with Copilot agent mode |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master | Create a custom Copilot agent |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development | Orchestrate multiple agents together |

> 📖 Prefer offline reading? All guides are available in the [`workshop/`](workshop/) folder.

---

## 🤝 Contributing

Contributions, ideas, and bug reports are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) before opening a pull request.

- 🐛 [Report a bug](../../issues/new)
- 💡 [Request a feature](../../issues/new)
- 📜 [Code of Conduct](CODE_OF_CONDUCT.md)
- 🔐 [Security Policy](SECURITY.md)

---

<div align="center">

Built with ❤️ and **GitHub Copilot** · Deploys automatically to GitHub Pages on push to `main`

</div>
