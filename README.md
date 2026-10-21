<div align="center">

<img src="https://arborithm.github.io/Kessho/logo.svg" alt="Kessho" width="160" />

# Kessho

**A structured memory for your AI agents — on your machine.**

A vault of Markdown files that belongs to you, organised so it stays under control as it grows, which your agents read and extend over MCP from one session to the next.

[![Latest release](https://img.shields.io/github/v/release/ArboRithm/Kessho?label=release&color=4C40D4)](https://github.com/ArboRithm/Kessho/releases/latest) [![Platforms](https://img.shields.io/badge/macOS%20%C2%B7%20Windows-4C40D4?label=platforms)](#download) [![Documentation](https://img.shields.io/badge/docs-arborithm.github.io-AD8B4A)](https://arborithm.github.io/Kessho/en/)

[**Download**](https://github.com/ArboRithm/Kessho/releases/latest) · [**Documentation**](https://arborithm.github.io/Kessho/en/) · [**MCP reference**](https://arborithm.github.io/Kessho/en/reference/mcp/) · [Français](README.fr.md)

<br />

<img src="https://arborithm.github.io/Kessho/captures/en/accueil.png" alt="The Kessho dashboard: the memory as a graph, recent deposits and the memory zones" width="900" />

</div>

## Why Kessho

An AI agent forgets everything when the session ends. The usual fix is a simple, flat memory — one file, or a pile of notes — that nobody tidies and whose growth is not controlled: sooner or later the agent drowns in it. Kessho gives you and your agent a **structured** memory instead: plain Markdown files in a folder you own, organised in zones (sessions, knowledge, procedures, principles, goals, people), projects and domains, with summaries, archives and health checks. The agent reads it to pick up where you left off and writes to it as the work goes on, and it stays navigable as it grows.

You keep the files. Your agent keeps the thread. Kessho keeps everything in order.

## Highlights

- **A memory that is just a folder** — Markdown files you can copy, back up and open with other tools. Compatible with Obsidian, without depending on it.
- **A built-in MCP server** — `kessho-mcp` exposes 62 tools to your agents: recall, search, archive, write notes, maintain the vault. Every tool is in the [MCP reference](https://arborithm.github.io/Kessho/en/reference/mcp/).
- **See your memory** — a dashboard, context keys to hand an agent so it finds where you were, and a graph of the relations between your notes.
- **A real editor** — read and write notes with blocks, tables, callouts, links between notes, find and replace, export.
- **Sync with git** — save and share the memory through a git remote of your choice, by hand or automatically.
- **Your agents, connected** — Kessho declares its MCP server in the AI tools installed on your machine.

## Works with your agents

Kessho speaks the [Model Context Protocol](https://modelcontextprotocol.io). Connect it from the app (**Settings › MCP connectors**), then just talk to your agent:

> _"Pick up where we left off on the invoicing project."_

The [agent guide](https://arborithm.github.io/Kessho/en/agent/) walks through real use cases: resume, search, write, archive, sync, maintain.

## Download

| Platform    | Requirements                     | File                             |
| ----------- | -------------------------------- | -------------------------------- |
| **macOS**   | Apple Silicon, macOS 11 or later | `Kessho_<version>_aarch64.dmg`   |
| **Windows** | x64                              | `Kessho_<version>_x64-setup.exe` |

Get them from the [latest release](https://github.com/ArboRithm/Kessho/releases/latest). The macOS build of **0.3.0**, the first public release, is available now; the Windows installer follows. Kessho then offers its own updates — nothing installs without your consent.

The macOS build is signed and notarized by Apple. The Windows installer is not signed yet: if SmartScreen warns you, choose **More info**, then **Run anyway**.

## Getting started

1. **Install** Kessho and walk through the five-step first launch.
2. **Choose your memory** — adopt an existing folder or create a new one.
3. **Connect your agent** from **Settings › MCP connectors**.
4. **Talk to your agent** — and watch the memory fill up in the app.

The [guide](https://arborithm.github.io/Kessho/en/guide/) covers each screen in detail.

## Privacy

Kessho runs on your machine. Your memory stays in your folders and belongs to you. There is no telemetry and no data collection.

## Support

- **Documentation** — [arborithm.github.io/Kessho](https://arborithm.github.io/Kessho/en/)
- **Bugs and suggestions** — [open an issue](https://github.com/ArboRithm/Kessho/issues)
- **Contact** — app@arborithm.fr

---

<sub>Kessho is published by ArboRithm and free to use under its [license agreement](LICENSE.md). Third-party components: [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).</sub>
