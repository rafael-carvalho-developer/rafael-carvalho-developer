<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg">
  <img alt="Rafael Carvalho - full-stack developer building with AI agents" src="./assets/banner-light.svg" width="100%">
</picture>

<br>

I'm a full-stack developer from Lisbon. I build products end to end, from the database to the interface to the server they run on, and these days most of that work goes through AI agents: I design the system and set the guardrails, Claude Code does a lot of the typing, and I review every diff before it ships.

Everything I build runs on a homelab I manage myself, so I care as much about deploys, backups and monitoring as I do about the code.

### What I'm building

- **Agentic workflows** - Claude Code skills, plugins, hooks and MCP servers, plus multi-agent pipelines that plan, review and verify changes before they land.
- **A self-hosted deploy platform** - a FastAPI control panel that turns a project folder into a running service: port allocation, systemd units, health checks with automatic rollback, daily backups and Telegram alerts, all behind Tailscale.
- **A local AI video studio** - transcription, subtitles, translation and dubbing with faster-whisper, edge-tts and FFmpeg, no paid APIs involved.
- **Commerce back-offices** - Shopify themes in Liquid and a Next.js + Prisma dashboard that runs a retail store: orders, stock, inbox parsing and push notifications.
- **Game servers** - Java plugins for a Minecraft network and Lua tooling for a FiveM roleplay server.

### How I work with AI

1. **Spec first.** Agents are fast, and vague instructions only make them wrong faster. The plan and the contract come before any code.
2. **Small commits, real rollbacks.** Git is the undo button for every deploy, so anything an agent changes is one step from reversed.
3. **Verify, don't trust.** Independent reviewer agents, tests and health checks run before anything reaches production.

### Stack

<table>
<tr><td><b>AI & agents</b></td><td>
<img alt="Claude" src="https://img.shields.io/badge/Claude-1f2328?style=flat-square&logo=claude&logoColor=D97757"> <img alt="Claude Code" src="https://img.shields.io/badge/Claude_Code-1f2328?style=flat-square&logo=claude&logoColor=D97757"> <img alt="MCP" src="https://img.shields.io/badge/MCP-1f2328?style=flat-square&logo=modelcontextprotocol&logoColor=white"> <img alt="Gemini" src="https://img.shields.io/badge/Gemini-1f2328?style=flat-square&logo=googlegemini&logoColor=8E75B2"> <img alt="faster-whisper" src="https://img.shields.io/badge/faster--whisper-1f2328?style=flat-square"> <img alt="Playwright" src="https://img.shields.io/badge/Playwright-1f2328?style=flat-square">
</td></tr>
<tr><td><b>Languages</b></td><td>
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-1f2328?style=flat-square&logo=typescript&logoColor=3178C6"> <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-1f2328?style=flat-square&logo=javascript&logoColor=F7DF1E"> <img alt="Python" src="https://img.shields.io/badge/Python-1f2328?style=flat-square&logo=python&logoColor=3776AB"> <img alt="PHP" src="https://img.shields.io/badge/PHP-1f2328?style=flat-square&logo=php&logoColor=777BB4"> <img alt="C#" src="https://img.shields.io/badge/C%23-1f2328?style=flat-square&logo=dotnet&logoColor=white"> <img alt="Java" src="https://img.shields.io/badge/Java-1f2328?style=flat-square&logo=openjdk&logoColor=white"> <img alt="Lua" src="https://img.shields.io/badge/Lua-1f2328?style=flat-square&logo=lua&logoColor=6E8BFF"> <img alt="Bash" src="https://img.shields.io/badge/Bash-1f2328?style=flat-square&logo=gnubash&logoColor=4EAA25"> <img alt="Liquid" src="https://img.shields.io/badge/Liquid-1f2328?style=flat-square">
</td></tr>
<tr><td><b>Frontend</b></td><td>
<img alt="React" src="https://img.shields.io/badge/React-1f2328?style=flat-square&logo=react&logoColor=61DAFB"> <img alt="Next.js" src="https://img.shields.io/badge/Next.js-1f2328?style=flat-square&logo=nextdotjs&logoColor=white"> <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-1f2328?style=flat-square&logo=tailwindcss&logoColor=06B6D4"> <img alt="Vite" src="https://img.shields.io/badge/Vite-1f2328?style=flat-square&logo=vite&logoColor=A78BFA"> <img alt="shadcn/ui" src="https://img.shields.io/badge/shadcn/ui-1f2328?style=flat-square&logo=shadcnui&logoColor=white"> <img alt="TanStack Query" src="https://img.shields.io/badge/TanStack_Query-1f2328?style=flat-square&logo=reactquery&logoColor=FF4154">
</td></tr>
<tr><td><b>Backend & data</b></td><td>
<img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-1f2328?style=flat-square&logo=fastapi&logoColor=009688"> <img alt="Node.js" src="https://img.shields.io/badge/Node.js-1f2328?style=flat-square&logo=nodedotjs&logoColor=5FA04E"> <img alt="Prisma" src="https://img.shields.io/badge/Prisma-1f2328?style=flat-square&logo=prisma&logoColor=white"> <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-1f2328?style=flat-square&logo=postgresql&logoColor=6DA5E0"> <img alt="Supabase" src="https://img.shields.io/badge/Supabase-1f2328?style=flat-square&logo=supabase&logoColor=3FCF8E"> <img alt="MariaDB" src="https://img.shields.io/badge/MariaDB-1f2328?style=flat-square&logo=mariadb&logoColor=C0765A"> <img alt="SQLite" src="https://img.shields.io/badge/SQLite-1f2328?style=flat-square&logo=sqlite&logoColor=74B4E0">
</td></tr>
<tr><td><b>Infra & platforms</b></td><td>
<img alt="Linux" src="https://img.shields.io/badge/Linux-1f2328?style=flat-square&logo=linux&logoColor=FCC624"> <img alt="Docker" src="https://img.shields.io/badge/Docker-1f2328?style=flat-square&logo=docker&logoColor=2496ED"> <img alt="Apache" src="https://img.shields.io/badge/Apache-1f2328?style=flat-square&logo=apache&logoColor=D22128"> <img alt="Tailscale" src="https://img.shields.io/badge/Tailscale-1f2328?style=flat-square&logo=tailscale&logoColor=white"> <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-1f2328?style=flat-square&logo=githubactions&logoColor=2088FF"> <img alt="Vercel" src="https://img.shields.io/badge/Vercel-1f2328?style=flat-square&logo=vercel&logoColor=white"> <img alt="Shopify" src="https://img.shields.io/badge/Shopify-1f2328?style=flat-square&logo=shopify&logoColor=95BF47"> <img alt="FFmpeg" src="https://img.shields.io/badge/FFmpeg-1f2328?style=flat-square&logo=ffmpeg&logoColor=5CB85C">
</td></tr>
</table>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rafael-carvalho-developer/rafael-carvalho-developer/output/snake-dark.svg">
  <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/rafael-carvalho-developer/rafael-carvalho-developer/output/snake-light.svg" width="100%">
</picture>

<p align="center">
  <a href="mailto:rafaelcarvalho.developer@gmail.com"><img alt="Email" src="https://img.shields.io/badge/rafaelcarvalho.developer@gmail.com-1f2328?style=for-the-badge&logo=gmail&logoColor=EA4335"></a>
</p>

<p align="center"><sub>Most of my work lives in private repositories. Happy to walk you through any of it.</sub></p>
