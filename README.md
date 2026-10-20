<p align="center">
<img src="https://capsule-render.vercel.app/api?type=rect&amp;color=0:0F172A,100:1D4ED8&amp;height=120&amp;section=header&amp;text=ThinkDonk&amp;fontSize=38&amp;fontAlignY=40&amp;desc=Tools%20for%20AI-assisted%20development&amp;descAlignY=70&amp;descSize=15&amp;fontColor=FFFFFF" width="100%" alt="ThinkDonk — Tools for AI-assisted development" />
</p>

I build practical tools for **AI-assisted development**: OpenCode extensions, MCP servers, and reusable skills for research and integration verification.

My projects help bring code context into a session, inspect what an agent did, and verify whether a change works.

我开发实用的 AI 编程工具，围绕 OpenCode、MCP 和开发技能，改善从项目调研、编码到结果验证的日常工作。

## OpenCode tools

| Project | What it helps with |
| :--- | :--- |
| [**vscode-opencode-v2**](https://github.com/ThinkDonk/vscode-opencode-v2) | Run the OpenCode v2 TUI inside VS Code and send file, selection, or diagnostic context into a session. |
| [**opencode-alert**](https://github.com/ThinkDonk/opencode-alert) | Get desktop and sound notifications for OpenCode sessions, with configurable filtering and quiet hours. |
| [**opencode-opentrace**](https://github.com/ThinkDonk/opencode-opentrace) | Inspect local OpenCode sessions, costs, tokens, tool calls, and sub-agent chains through a read-only dashboard. |

## MCP & developer skills

| Project | What it helps with |
| :--- | :--- |
| [**ast-grep-mcp**](https://github.com/ThinkDonk/ast-grep-mcp) | Search and replace code by syntax structure through MCP, with dry-run previews before applying edits. |
| [**github-landscape**](https://github.com/ThinkDonk/github-landscape) | Research similar GitHub projects with a Codex skill and Python helper; compare features, maintenance evidence, and limitations. |
| [**commit-test**](https://github.com/ThinkDonk/commit-test) | Scope integration checks to Git changes, verify behavior through real pages, and keep reusable knowledge separate from each run's evidence. |

See each repository for installation, supported environments, and release status.

## How I build

- **Focused tools:** solve a concrete problem and keep dependencies explicit.
- **Inspectable behavior:** make tool activity, changes, and results easier to understand.
- **Evidence before conclusions:** distinguish what was verified from what remains untested.

## Beyond developer tooling

[**VideoNexus**](https://github.com/ThinkDonk/VideoNexus) is a GB28181 video supervision portal with per-channel authorization, audit trails, and asynchronous recording downloads. Built with FastAPI and Vue 3, it uses an existing WVP-GB28181-pro + ZLMediaKit setup for streaming and provides Docker Compose deployment for the portal.

<details>
<summary>More projects &amp; earlier work</summary>

- [**llm-safe-write**](https://github.com/ThinkDonk/llm-safe-write) — An incremental editing skill for large or CJK files when an AI tool's file-writing calls hit truncation errors.
- [**sso-service**](https://github.com/ThinkDonk/sso-service) — An OIDC authentication service for Outline Wiki.
- [**ExcelToSqlServer**](https://github.com/ThinkDonk/ExcelToSqlServer) — An earlier ASP.NET WebForms example for Excel import, duplicate checking, and transactional bulk inserts.

</details>

## Working with

<img src="https://img.shields.io/badge/TypeScript-1D4ED8?style=flat-square&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" /> <img src="https://img.shields.io/badge/Python-1D4ED8?style=flat-square&amp;logo=python&amp;logoColor=white" alt="Python" /> <img src="https://img.shields.io/badge/JavaScript-1D4ED8?style=flat-square&amp;logo=javascript&amp;logoColor=white" alt="JavaScript" /> <img src="https://img.shields.io/badge/Vue.js-1D4ED8?style=flat-square&amp;logo=vuedotjs&amp;logoColor=white" alt="Vue.js" /> <img src="https://img.shields.io/badge/FastAPI-1D4ED8?style=flat-square&amp;logo=fastapi&amp;logoColor=white" alt="FastAPI" /> <img src="https://img.shields.io/badge/Docker-1D4ED8?style=flat-square&amp;logo=docker&amp;logoColor=white" alt="Docker" />

Questions, bug reports, and practical use cases are welcome in each project's Issues.
