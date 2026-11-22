<div align="center">

# 0xWulf

### 🎓 Computer Science Student | 🐧 Linux Enthusiast | 📚 Lifelong Learner

*Building small tools that help me study better and solve real-world problems*

[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-0xwulf.dev-blue?style=for-the-badge)](https://0xwulf.dev)
[![Email](https://img.shields.io/badge/📧_Email-dev@0xwulf.dev-red?style=for-the-badge)](mailto:dev@0xwulf.dev)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/hexawulf)

</div>

---

## 🚀 About Me

🎓 **B.A. Computer Science** student at International University of Applied Sciences (IU Germany)<br>
🎓 **M.A. in Sinology** — Background in classical Chinese language and philosophy<br>
🐧 **Linux-first workflows** — Ubuntu is my daily driver for development and study · [`zk@linuxsvr`](https://linuxsvr.org)<br>
📚 **Learning Journey** — Currently learning Vue.js<br>
🍓 **Self-Hosted** — Most of my app projects run locally on [piapps.dev](https://piapps.dev), my Raspberry Pi 5 server running Ubuntu 26.04 + Nginx

---

## 🛠️ Featured Projects

<table>

<tr>
<td width="50%" style="vertical-align: top;">

<h3>🍓 <a href="https://github.com/hexawulf/PiDeck">PiDeck</a></h3>
<p><em>Admin dashboard for my self-hosted servers</em></p>

<p><strong>🚀 <a href="https://pideck.piapps.dev">Live Demo</a> | 📂 <a href="https://github.com/hexawulf/PiDeck">Source</a> | 🏷️ <a href="https://github.com/hexawulf/PiDeck/releases/tag/v2.12.0">v2.12</a></strong></p>

<p>Control hub for my Raspberry Pi homelab. A dashboard running on my Pi 5 that pulls from small read-only agents across my LAN machines, cloud VPSes (over WireGuard) and a Synology NAS, showing live metrics with 24 h history, remote logs, Docker and PM2 apps, systemd services with alerts, and cron jobs, all behind Google sign-in.</p>

<p><strong>Tech Stack:</strong> React 18 • TypeScript • Vite • Tailwind • Express • PostgreSQL • Playwright</p>

</td>
<td width="50%" style="vertical-align: top;">

<h3>⏱️ <a href="https://github.com/hexawulf/PiTasker">PiTasker</a></h3>
<p><em>Web UI for the crontab on my servers</em></p>

<p><strong>🚀 <a href="https://pitasker.piapps.dev">Live Demo</a> | 📂 <a href="https://github.com/hexawulf/PiTasker">Source</a> | 🏷️ <a href="https://github.com/hexawulf/PiTasker/releases/tag/v2.3.1">v2.3</a></strong></p>

<p>A web UI for cron on my Raspberry Pi servers. Edit jobs with a diff shown before every write, run them on demand, and keep a run history. Small read-only agents pull in everything scheduled across my other machines too, both crontabs and systemd timers.</p>

<p><strong>Tech Stack:</strong> React 18 • TypeScript • Vite • Tailwind • Express • PostgreSQL • Drizzle • Playwright</p>

</td>
</tr>

<tr>
<td width="50%" style="vertical-align: top;">

<h3>🐍 <a href="https://github.com/hexawulf/py-scratchpad">py-scratchpad</a></h3>
<p><em>Browser-only Python scratchpad</em></p>

<p><strong>🚀 <a href="https://py-scratchpad.com">Live Demo</a> | 📂 <a href="https://github.com/hexawulf/py-scratchpad">Source</a> | 🏷️ <a href="https://github.com/hexawulf/py-scratchpad/releases/tag/v0.3.9">v0.3.9</a> | 🐋 <a href="https://hub.docker.com/r/0xwulf/py-scratchpad">Docker Hub</a></strong></p>

<p>A small Python editor to keep open next to a course video: run code with Pyodide, syntax highlighting, autosave, and byte-for-byte .py import/export. Everything stays in the browser — no backend, no accounts.</p>

<p><strong>Tech Stack:</strong> TypeScript • Vite • CodeMirror 6 • Pyodide • Vitest • Docker</p>

</td>
<td width="50%" style="vertical-align: top;">

<h3>🗄️ <a href="https://github.com/hexawulf/sql-scratchpad">sql-scratchpad</a></h3>
<p><em>Letos-style SQL playground in the browser</em></p>

<p><strong>🚀 <a href="https://sql-scratchpad.com">Live Demo</a> | 📂 <a href="https://github.com/hexawulf/sql-scratchpad">Source</a> | 🏷️ <a href="https://github.com/hexawulf/sql-scratchpad/releases/tag/v0.3.6">v0.3.6</a> | 🐋 <a href="https://hub.docker.com/r/0xwulf/sql-scratchpad">Docker Hub</a></strong></p>

<p>Real MariaDB workspaces in the browser: a schema tree, a multi-tab SQL editor and a result grid, with a sample library dataset or your own imported .sql. Nothing is stored; each workspace runs as its own database user and is deleted after 2 h idle.</p>

<p><strong>Tech Stack:</strong> Vue 3 • TypeScript • CodeMirror 6 • Fastify 5 • MariaDB 11.4 • Playwright • Docker</p>

</td>
</tr>

<tr>
<td width="50%" style="vertical-align: top;">

<h3>🐳 <a href="https://github.com/hexawulf/ContainerYard">ContainerYard</a></h3>
<p><em>Log-first Docker observability dashboard</em></p>

<p><strong>🚀 <a href="https://containeryard.org">Website</a> | 📂 <a href="https://github.com/hexawulf/ContainerYard">Source</a> | 🏷️ <a href="https://github.com/hexawulf/ContainerYard/releases/tag/v5.5.0">v5.5</a> | 🐋 <a href="https://hub.docker.com/r/0xwulf/containeryard">Docker Hub</a></strong></p>

<p>Real-time log streaming, Compose stack views and per-container metrics across several Docker and cAdvisor hosts, with roles and an audit log. Ships as a multi-arch image (amd64 and arm64) with SBOM and provenance from CI.</p>

<p><strong>Tech Stack:</strong> React 18 • TypeScript • Express • Prisma • SQLite • Redis • Docker</p>

</td>
<td width="50%" style="vertical-align: top;">

<h3>📝 <a href="https://github.com/hexawulf/MarkdownMate">MarkdownMate</a></h3>
<p><em>Markdown editor with live preview</em></p>

<p><strong>🚀 <a href="https://markdownmate.org">Live Demo</a> | 📂 <a href="https://github.com/hexawulf/MarkdownMate">Source</a> | 🏷️ <a href="https://github.com/hexawulf/MarkdownMate/releases/tag/v3.5.0">v3.5</a></strong></p>

<p>Write and preview Markdown side by side, with math (KaTeX) and code highlighting. Documents stay in the browser and export to .md, HTML or PDF. I use it for course notes and README files.</p>

<p><strong>Tech Stack:</strong> React 18 • TypeScript • Vite • Tailwind • Monaco Editor • Vitest</p>

</td>
</tr>

</table>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=hexawulf&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hexawulf&layout=compact&langs_count=8&theme=dark"/>

</div>

---

## 💻 Tech Stack & Skills

### **Languages**
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### **Frontend**
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

### **Backend & Database**
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### **Tools & Platforms**
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 🔭 Current Focus

- 📚 **Learning Vue.js & Node.js** — Working through courses and building real projects along the way
- 🔒 **Hardening my self-hosted apps** — Tests, CI and security fixes across the projects above, one audit at a time
- 🐧 **Linux-First Development** — Ubuntu is my daily environment for coding, studying, and experimenting

---

## 📈 Contribution Activity

<div align="center">

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=hexawulf&theme=react-dark&hide_border=true)

</div>
