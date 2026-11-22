# Awesome-Terminal-Emulator-CLI-Utilities
# Awesome-Terminal-Emulator-CLI-Utilities

## Top Terminal Emulator & CLI Utilities Ecosystem



**Curated List of SaaS/Cloud-Synced Terminals & Open-Source GitHub Projects**  

*Focused on GPU-Accelerated Terminal Emulators, SSH Workspaces, Multiplexers & Modern CLI Utilities*  

**Last updated: November 2026**



This repository tracks notable **SaaS/cloud-enabled terminal platforms** and **open-source projects** for **Terminal Emulators & CLI Utilities**. These tools power daily command-line workflows with GPU-accelerated rendering, Kitty graphics protocol support, AI-assisted command blocks, encrypted SSH/SFTP sync, and modern Rust/Go CLI replacements.



**Examples** include AnalyseDeCircuit/oxideterm, Ghostty, WezTerm, Alacritty, Kitty, Rio, Tabby, Windows Terminal, iTerm2, Hyper, Warp, Termius, SecureCRT, and Wave Terminal.



**Open-source emphasis**: This list heavily expands on active open-source GPU-accelerated terminal emulators, native Rust/GPUI workspaces, terminal multiplexers, prompts, and modern CLI utilities — ideal for developers, sysadmins, and terminal power users seeking speed, zero telemetry, and full customization.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Warp](https://warp.dev)**  

  Modern, GPU-accelerated terminal featuring IDE-style input editing, command blocks, built-in AI agents, and cloud-synced team workflows (Warp Drive).



- **[Termius](https://termius.com)**  

  Cross-platform SSH client and terminal workspace with encrypted cloud vault sync for hosts, keys, port forwarding, and SFTP across desktop and mobile.



- **[SecureCRT (VanDyke Software)](https://vandyke.com)**  

  Commercial enterprise terminal emulator supporting SSH, Telnet, serial sessions, multi-tabbed scripting, and centralized session management.



- **[Xshell (NetSarang)](https://netsarang.com)**  

  Proprietary SSH and terminal emulator for Windows offering tabbed multi-session management, dynamic port forwarding, and enterprise authentication.



- **[Shellngn](https://shellngn.com)**  

  Cloud-based SSH, SFTP, VNC, and RDP client accessible directly from any web browser with multi-session workspace management.





## Open-Source GitHub Projects



- **[OxideTerm (AnalyseDeCircuit/oxideterm)](https://github.com/AnalyseDeCircuit/oxideterm)**  

  Native, GPU-rendered workspace written in Rust and GPUI for local shells and remote SSH/SFTP machines with MCP/AI tools, port forwarding, zero WebView, and zero telemetry.



- **[Ghostty](https://github.com)**  

  Fast, feature-rich, cross-platform terminal emulator written in Zig that uses native platform UI alongside GPU-accelerated rendering and Kitty graphics support.



- **[WezTerm](https://github.com)**  

  GPU-accelerated cross-platform terminal emulator and multiplexer written in Rust, configured in Lua, with built-in SSH domains, panes, and ligature support.



- **[Alacritty](https://github.com)**  

  Minimalist, ultra-fast cross-platform terminal emulator written in Rust focusing on raw GPU rendering speed and simplicity.



- **[Kitty](https://github.com)**  

  Fast, feature-rich GPU-based terminal emulator supporting the Kitty graphics protocol, ligatures, tabs, splits, and extensible Python "kittens".



- **[Rio](https://github.com)**  

  Hardware-accelerated terminal emulator written in Rust built to run natively on desktop as well as in the browser via WebAssembly.



- **[Tabby](https://github.com)**  

  Highly configurable cross-platform terminal emulator, SSH, and serial client featuring integrated SFTP, split panes, and a rich plugin ecosystem.



- **[Windows Terminal](https://github.com)**  

  Modern, fast, open-source terminal application for Windows supporting multiple tabs, panes, GPU-accelerated DirectWrite/DirectX text rendering, and custom themes.



- **[iTerm2](https://github.com)**  

  Feature-packed open-source terminal emulator for macOS with split panes, hotkey windows, shell integration, inline images, and Python scripting.



- **[Hyper](https://github.com)**  

  Extensible cross-platform terminal emulator built on web technologies (HTML/CSS/JS) with an extensive plugin and theme ecosystem.



- **[Wave Terminal](https://github.com)**  

  Open-source, AI-native terminal workspace that embeds graphical widgets, file previews, web browsers, and persistent remote SSH blocks directly alongside CLI sessions.



- **[foot](https://codeberg.org)**  

  Fast, lightweight, Wayland-native terminal emulator written in C with server/client daemon mode and minimal resource usage.



- **[Zellij](https://github.com)** & **[tmux](https://github.com)**  

  Essential open-source terminal multiplexers for persistent sessions, split panes, floating windows, and remote SSH resilience.



### Additional Strong Open-Source Options



- **[Starship](https://github.com)** — Minimal, blazing-fast, and customizable cross-shell prompt written in Rust.

- **[Atuin](https://github.com)** — Magical shell history replacement that stores commands in SQLite with optional end-to-end encrypted sync.

- **[bat](https://github.com)** — `cat` clone with syntax highlighting, line numbers, and Git integration.

- **[ripgrep (rg)](https://github.com)** — Ultra-fast recursive line-oriented search tool that respects `.gitignore`.

- **[fzf](https://github.com)** — General-purpose command-line fuzzy finder for files, command history, processes, and Git commits.

- **[zoxide](https://github.com)** — Smarter `cd` command written in Rust that tracks directory frequency for instant navigation.

- **[eza](https://github.com)** — Modern, actively maintained replacement for `ls` with icons, tree views, and Git status.

- **[tldr / tealdeer](https://github.com)** — Very fast Rust implementation of `tldr` providing practical, example-driven CLI command cheatsheets.



**Frameworks for building custom systems**: Combine **Ghostty**, **WezTerm**, or **OxideTerm** with **Zellij** / **tmux**, **Starship**, **Atuin**, and **fzf + ripgrep** for a cohesive, ultra-fast terminal and remote SSH workflow.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/proprietary or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Always verify SSH host keys, keychain storage, and credential security when connecting to production servers or syncing shell history across machines.

- GPU-accelerated emulators require compatible graphics drivers (Metal, Vulkan, DirectX, or OpenGL) for optimal rendering performance.



---



**Made for terminal enthusiasts, sysadmins, developers, and open-source contributors.**  

Let's make terminal emulators and CLI utilities faster, extensible, and open to everyone.
