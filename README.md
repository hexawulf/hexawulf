<div align="center">

# 0xWulf

### 🎓 Computer Science Student · 🐧 Linux & Homelab Operator · 🛠️ Full-Stack Builder

*Building self-hosted developer tools, study sandboxes, and multi-host fleet dashboards*

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-0xwulf.dev-0d9488?style=for-the-badge)](https://0xwulf.dev)
[![Homelab](https://img.shields.io/badge/🍓_Homelab-piapps.dev-C51A4A?style=for-the-badge)](https://piapps.dev)
[![Workstation](https://img.shields.io/badge/🐧_Workstation-linuxsvr.org-E95420?style=for-the-badge)](https://linuxsvr.org)
[![Email](https://img.shields.io/badge/📧_Email-dev@0xwulf.dev-2563eb?style=for-the-badge)](mailto:dev@0xwulf.dev)

</div>

---

## 🚀 About Me

- 🎓 **B.A. Computer Science** student at International University of Applied Sciences (IU Germany) — focused on Java, SQL, software engineering, and web architecture
- 📜 **M.A. in Sinology** — background in classical Chinese language, philology, and philosophy
- 🍓 **Self-Hosted Infrastructure** — I run a multi-node Ubuntu 26.04 homelab fronted by a Raspberry Pi 5 edge server ([piapps.dev](https://piapps.dev)) with Nginx, Cloudflare, Docker, and WireGuard connecting LAN hosts, a Synology NAS, and cloud VPSes
- 🧪 **Quality & Hardening First** — every project below ships with automated CI, unit/integration suites (JUnit / Vitest), Playwright E2E browser tests, and dependency/container scanning
- 🐧 **Linux Daily Driver** — Ubuntu across workstation ([`zk@linuxsvr`](https://linuxsvr.org)) and servers

---

## 🛠️ Featured Projects

<table>

<tr>
<td width="50%" valign="top">

### 🍓 [PiDeck](https://github.com/hexawulf/PiDeck)
*Multi-host admin dashboard for my Raspberry Pi homelab*

[![Live](https://img.shields.io/badge/Live-pideck.piapps.dev-0d9488?style=flat-square&logo=raspberrypi&logoColor=white)](https://pideck.piapps.dev)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/hexawulf/PiDeck)
[![Release](https://img.shields.io/badge/Release-v2.12.1-2563eb?style=flat-square)](https://github.com/hexawulf/PiDeck/releases/tag/v2.12.1)

Control hub running on my Raspberry Pi 5 that polls small read-only agents across LAN machines, cloud VPSes (over WireGuard), and a Synology NAS. Shows live system metrics with 24 h history, remote logs, Docker & PM2 apps, systemd services with alerts, and cron jobs behind Google sign-in.

`React 19` `TypeScript` `Vite` `Tailwind` `Express` `PostgreSQL` `Playwright`

</td>
<td width="50%" valign="top">

### ⏱️ [PiTasker](https://github.com/hexawulf/PiTasker)
*Web UI for crontabs and scheduled tasks across a Linux fleet*

[![Live](https://img.shields.io/badge/Live-pitasker.piapps.dev-0d9488?style=flat-square&logo=linux&logoColor=white)](https://pitasker.piapps.dev)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/hexawulf/PiTasker)
[![Release](https://img.shields.io/badge/Release-v2.3.2-2563eb?style=flat-square)](https://github.com/hexawulf/PiTasker/releases/tag/v2.3.2)

Manage cron jobs on a Raspberry Pi server with a pre-write diff preview, on-demand execution, and full run history. Lightweight read-only agents pull in scheduled crontabs and systemd timers from every other machine in the fleet.

`React 18` `TypeScript` `Vite` `Tailwind` `Express` `PostgreSQL` `Drizzle` `Playwright`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🐳 [ContainerYard](https://github.com/hexawulf/ContainerYard)
*Log-first multi-host Docker observability dashboard*

[![Website](https://img.shields.io/badge/Website-containeryard.org-0d9488?style=flat-square&logo=docker&logoColor=white)](https://containeryard.org)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/hexawulf/ContainerYard)
[![Release](https://img.shields.io/badge/Release-v5.5.2-2563eb?style=flat-square)](https://github.com/hexawulf/ContainerYard/releases/tag/v5.5.2)
[![Docker Hub](https://img.shields.io/badge/Docker-0xwulf%2Fcontaineryard-2496ED?style=flat-square&logo=docker&logoColor=white)](https://hub.docker.com/r/0xwulf/containeryard)

Real-time log streaming, Compose stack views, and per-container metrics across multiple Docker and cAdvisor hosts, complete with RBAC roles and an audit log. Published as a multi-arch (`amd64` / `arm64`) image with CI SBOM and provenance attestations.

`React 18` `TypeScript` `Express` `Prisma` `SQLite` `Redis` `Docker`

</td>
<td width="50%" valign="top">

### 🔐 [KeyJolt](https://github.com/hexawulf/KeyJolt)
*Instant, ephemeral PGP & SSH key pair generator*

[![Live](https://img.shields.io/badge/Live-keyjolt.dev-0d9488?style=flat-square&logo=spring&logoColor=white)](https://keyjolt.dev)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/hexawulf/KeyJolt)
[![Release](https://img.shields.io/badge/Release-v1.3.0-2563eb?style=flat-square)](https://github.com/hexawulf/KeyJolt/releases/tag/v1.3.0)

Generates RSA PGP and Ed25519/RSA-4096 SSH key pairs with 128-bit token download links, Bucket4j rate limiting, strict CSP/HSTS headers, and secure random-overwrite deletion after 5 minutes. Backed by 100 JUnit tests (80% JaCoCo coverage gate), Playwright smoke tests, and Trivy scanning.

`Java 17` `Spring Boot 4.1` `Spring Security` `Bouncy Castle` `Thymeleaf` `JUnit 5` `Playwright`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🐍 [py-scratchpad](https://github.com/hexawulf/py-scratchpad)
*Zero-backend Python scratchpad in the browser*

[![Live](https://img.shields.io/badge/Live-py--scratchpad.com-0d9488?style=flat-square&logo=python&logoColor=white)](https://py-scratchpad.com)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/hexawulf/py-scratchpad)
[![Release](https://img.shields.io/badge/Release-v0.3.10-2563eb?style=flat-square)](https://github.com/hexawulf/py-scratchpad/releases/tag/v0.3.10)
[![Docker Hub](https://img.shields.io/badge/Docker-0xwulf%2Fpy--scratchpad-2496ED?style=flat-square&logo=docker&logoColor=white)](https://hub.docker.com/r/0xwulf/py-scratchpad)

A fast Python editor built to sit next to a course lecture: runs Python client-side via WebAssembly (Pyodide) with edge-cached cold loads, CodeMirror 6 highlighting, autosave, and byte-for-byte `.py` import/export. No backend, no accounts.

`TypeScript` `Vite` `CodeMirror 6` `Pyodide (WASM)` `Vitest` `Docker`

</td>
<td width="50%" valign="top">

### 🗄️ [sql-scratchpad](https://github.com/hexawulf/sql-scratchpad)
*Ephemeral MariaDB SQL workspaces in the browser*

[![Live](https://img.shields.io/badge/Live-sql--scratchpad.com-0d9488?style=flat-square&logo=mariadb&logoColor=white)](https://sql-scratchpad.com)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/hexawulf/sql-scratchpad)
[![Release](https://img.shields.io/badge/Release-v0.3.7-2563eb?style=flat-square)](https://github.com/hexawulf/sql-scratchpad/releases/tag/v0.3.7)
[![Docker Hub](https://img.shields.io/badge/Docker-0xwulf%2Fsql--scratchpad-2496ED?style=flat-square&logo=docker&logoColor=white)](https://hub.docker.com/r/0xwulf/sql-scratchpad)

Real isolated MariaDB 11.4 databases in the browser with a live schema tree, multi-tab SQL editor, and result grid. Load the built-in library dataset or import your own `.sql` dump; each workspace runs under its own database user and auto-purges after 2 h idle.

`Vue 3` `TypeScript` `CodeMirror 6` `Fastify 5` `MariaDB 11.4` `Playwright` `Docker`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### 🧩 [CodePatchwork](https://github.com/hexawulf/CodePatchwork)
*Keyboard-first visual code snippet library*

[![Live](https://img.shields.io/badge/Live-codepatchwork.com-0d9488?style=flat-square)](https://codepatchwork.com)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/hexawulf/CodePatchwork)
[![Release](https://img.shields.io/badge/Release-v2.1.1-2563eb?style=flat-square)](https://github.com/hexawulf/CodePatchwork/releases/tag/v2.1.1)

Organize, search, and share code snippets with multi-facet language/tag filtering, an inline Snippet Inspector Drawer, a `⌘K`/`Ctrl+K` command palette, collections, five Prism syntax themes, and drag-and-drop JSON round-trip import/export.

`React 18` `TypeScript` `Tailwind` `Radix UI` `Express` `PostgreSQL` `Drizzle` `Playwright`

</td>
<td width="50%" valign="top">

### 📝 [MarkdownMate](https://github.com/hexawulf/MarkdownMate)
*Side-by-side Markdown editor with KaTeX math & live preview*

[![Live](https://img.shields.io/badge/Live-markdownmate.org-0d9488?style=flat-square&logo=markdown&logoColor=white)](https://markdownmate.org)
[![Source](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github)](https://github.com/hexawulf/MarkdownMate)
[![Release](https://img.shields.io/badge/Release-v3.5.1-2563eb?style=flat-square)](https://github.com/hexawulf/MarkdownMate/releases/tag/v3.5.1)

Write and preview Markdown in real time on the Monaco Editor with KaTeX math rendering and syntax highlighting. Everything stays local in the browser with one-click export to `.md`, HTML, or PDF—built for CS course notes and technical docs.

`React 18` `TypeScript` `Vite` `Tailwind` `Monaco Editor` `KaTeX` `Vitest`

</td>
</tr>

</table>

> 🍓 **More self-hosted apps on [piapps.dev](https://piapps.dev):** [**SnippetMate**](https://snippetmate.com) ([Source](https://github.com/hexawulf/SnippetMate) · `v2.1.0` · Vue 3 + MySQL web clipper) · [**TableTamer**](https://tabletamer.piapps.dev) ([Source](https://github.com/hexawulf/tabletamer) · `v1.3.0` · browser CSV editor) · [**Reading Habit Tracker**](https://mybooks.piapps.dev) ([Source](https://github.com/hexawulf/reading-habit-tracker) · `v1.3.0` · Goodreads CSV analytics) · [**Stocky**](https://stocky.piapps.dev) ([Source](https://github.com/hexawulf/stocky) · `v1.1.0` · homelab hardware tracker)

---

## 💻 Tech Stack & Tools

### **Languages**
![Java](https://img.shields.io/badge/Java_17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### **Frontend**
![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### **Backend & Databases**
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js_22-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=for-the-badge&logo=fastify&logoColor=white)
![Express.js](https://img.shields.io/badge/Express-404D59?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### **Infrastructure, Testing & Workflow**
![Ubuntu](https://img.shields.io/badge/Ubuntu_26.04-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 📊 GitHub Stats & Activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=hexawulf&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&include_all_commits=true&count_private=true" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=hexawulf&show_icons=true&theme=default&hide_border=true&include_all_commits=true&count_private=true" />
  <img height="175em" alt="0xWulf's GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=hexawulf&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&include_all_commits=true&count_private=true" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=hexawulf&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=hexawulf&layout=compact&langs_count=8&theme=default&hide_border=true" />
  <img height="175em" alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hexawulf&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117" />
</picture>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=hexawulf&theme=react-dark&hide_border=true&bg_color=0d1117" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=hexawulf&theme=github-light&hide_border=true" />
  <img alt="GitHub Activity Graph" src="https://github-readme-activity-graph.vercel.app/graph?username=hexawulf&theme=react-dark&hide_border=true&bg_color=0d1117" />
</picture>

</div>
