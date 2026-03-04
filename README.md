<h1 align="center">Hi, I'm Weihao Li (L-Rocket)</h1>
<p align="center">
  CS Student @ Duke ECE · Building systems, tooling, and agent platforms
</p>

<p align="center">
  <a href="https://github.com/L-Rocket">
    <img src="https://img.shields.io/github/followers/L-Rocket?label=Followers&style=for-the-badge" alt="GitHub Followers" />
  </a>
  <a href="https://github.com/L-Rocket?tab=repositories">
    <img src="https://img.shields.io/badge/Focus-Systems%20%7C%20AI%20%7C%20Performance-1f6feb?style=for-the-badge" alt="Focus" />
  </a>
  <a href="https://l-rocket.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-Live-0a7ea4?style=for-the-badge" alt="Portfolio" />
  </a>
</p>

## About Me

- I enjoy building practical software with clear architecture and measurable performance.
- My current work spans **Go backends**, **C++ performance tooling**, and **AI agent orchestration**.
- I care about DX, maintainability, and shipping complete, documented projects.

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/WebSocket-4B5563?style=flat-square" alt="WebSocket" />
</p>

## Featured Projects

### [EchoCenter](https://github.com/L-Rocket/EchoCenter)
Modular multi-agent management hub with real-time WebSocket messaging, a Butler coordinator, React dashboard, and persistent chat history. Recent update adds backend unit tests (auth/config/repository), tighter SQLite unique-constraint handling, and bilingual contribution guides.

### [nanoCache](https://github.com/L-Rocket/nanoCache)
Sharded in-memory key-value store implemented in both C++17 and Go to compare concurrency models, locking strategies, and performance tradeoffs. Latest benchmark refresh (2026-03-04) shows C++ leading by 2.62x-5.35x across key scenarios.

### [BlockVector](https://github.com/L-Rocket/BlockVector)
Header-only C++17 container with chunked storage for pointer stability and zero-copy growth where `std::vector` reallocation is costly. README now includes local benchmark data and pointer-stability comparison vs `std::vector`.

### [duck-ddns](https://github.com/L-Rocket/duck-ddns)
Lightweight Go client for automatic DuckDNS updates, batch domain refresh, and easy Linux deployment with service/log rotation support.

### [Tanto](https://github.com/L-Rocket/Tanto)
Global productivity tool for Windows developers (AutoHotkey v2), bringing Vim-style navigation and one-shot editing actions system-wide.

## Recent Updates (Mar 2026)

- **EchoCenter**: Added backend unit tests for auth/config/repository modules and hardened unique-constraint detection logic in SQLite repository handling.
- **nanoCache**: Added CI workflow for Go/C++ test + benchmark smoke checks, aligned C++/Go benchmark workload, and published refreshed baseline ops/s results.
- **BlockVector**: Added local performance comparison section covering end-to-end operations, heavy-object append behavior, and pointer stability.

## Links

- Portfolio: https://l-rocket.github.io/
- LinkedIn: https://www.linkedin.com/in/weihao-li-4569043a7/
- Email: weihao.li@duke.edu
