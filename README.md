# CodeLeash — AI Coding Agent Guardrail & Forensics

**Put a seatbelt & Black Box on Cursor, Claude Code, GitHub Copilot, Windsurf, and CLI coding agents.**

[**Website & Live Demo →**](https://samesaja.github.io/codeleash/) • [**Install Free in VS Code**](https://marketplace.visualstudio.com/items?itemName=codeleash.codeleash) • [**OpenVSX (Cursor / Windsurf)**](https://open-vsx.org/extension/codeleash/codeleash)

![CodeLeash Live Demo](https://samesaja.github.io/codeleash/demo.gif)

---

## Key Capabilities

- **Agent vs. Human Forensics Timeline:** Native Rust + SQLite WAL engine distinguishes manual developer saves from high-velocity multi-file AI agent bursts—even from external CLI agents (`claude`, `aider`, `codex`).
- **Flag-Aware SSH Destructive Command Firewall:** Intercepts inline remote SSH commands inside IDE terminals (`rm -rf`, `sudo`, `mkfs`, `systemctl stop`, `DROP DATABASE`, plus custom regexes) and aborts before a packet leaves your workstation.
- **Zero-Token LSP Blast Radius Detection:** Queries VS Code's built-in Language Server (`executeReferenceProvider`) on modified symbol columns with **0 LLM tokens** and warns immediately when an AI edit silently impacts shared symbols across caller files.
- **1-Click Reverse-Patch Rollback & Smart Diff Merge:** Revert individual faulty AI edits cleanly or fall back to VS Code's native Side-by-Side Diff Merge when newer manual changes overlap.
- **100% Local-First Privacy:** Zero cloud uploads, zero source-code telemetry. Every snapshot lives locally on your machine.

---

## Community (Free) vs. CodeLeash Pro ($19 Lifetime)

| Feature | Community (Free) | CodeLeash Pro |
| :--- | :---: | :---: |
| Real-time Human vs. AI Agent Timeline | Rolling 24h Window | **Unlimited Retention** |
| 1-Click Reverse-Patch Rollback & Diff Merge | Included | **Included** |
| Built-in SSH Destructive Command Firewall | Core Rules | **Core + Custom Regex Rules** |
| Zero-Token LSP Blast Radius Alerts | Preview (up to 3 files) | **Unlimited + Red Alert Guard** |
| Client-Ready "Proof of Effort" Markdown Export | — | **Included** |

---

## Bug Reports & Feature Requests

Found an edge case in an OpenSSH flag combination or Language Server provider? Open an issue in this repository's [**Issue Tracker**](https://github.com/samesaja/codeleash/issues).
