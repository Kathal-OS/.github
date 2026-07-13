<div align="center">

<img src="https://img.shields.io/badge/BakeWeb-KATHAL%20OS-2ea44f?style=for-the-badge&logo=jsonwebtokens&logoColor=white" alt="KATHAL OS" />

# 🌳 KATHAL OS
<p>
<img src="https://img.shields.io/badge/status-in%20development-yellow?style=flat-square" />
<img src="https://img.shields.io/badge/license-open--source-blue?style=flat-square" />
<img src="https://img.shields.io/badge/language-Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/frontend-Next.js-black?style=flat-square&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/docker-native-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square" />
</p>

<img width="986" height="538" alt="image" src="https://github.com/user-attachments/assets/6e0ef0fd-6a3b-4fcc-a5f6-2292b2d12ba6" />
### An AI-Native Hosting & Development Operating System

**Built by [BakeWeb](#-built-by) — Open Source Forever**


<p>
<a href="https://your-domain.com"><b>Website</b></a> •
<a href="https://docs.your-domain.com"><b>Documentation</b></a> •
<a href="#"><b>Discord</b></a> •
<a href="../../discussions"><b>Discussions</b></a> •
<a href="../../issues"><b>Issues</b></a>
</p>

</div>

<br/>

<div align="center">
<img src="https://img.shields.io/badge/-One%20Platform%20•%20Infinite%20Infrastructure-111827?style=for-the-badge" />
</div>

<br/>

---
<div align="center">
  
## 📖 Table of Contents

<table>
<tr>
<td valign="top" width="33%">

**Overview**
- 🚀 [About](#-about)
- 💡 [Why KATHAL OS](#-why-kathal-os)
- 🏗️ [Architecture](#-architecture)
- 📦 [Projects](#-projects)

</td>
<td valign="top" width="33%">

**Build**
- 🧱 [Tech Stack](#-tech-stack)
- ⚡ [Getting Started](#-getting-started)
- 🗺️ [Roadmap](#-roadmap)

</td>
<td valign="top" width="33%">

**Community**
- 🤝 [Contributing](#-contributing)
- 💬 [Community](#-community)
- ❤️ [Built By](#-built-by)
- 📄 [License](#-license)

</td>
</tr>
</table>

---

## 🚀 About

**BakeWeb** builds open-source infrastructure software that makes deploying, hosting, automating, and managing applications simple, secure, and scalable.

Our flagship product, **KATHAL OS**, is a next-generation, AI-native Hosting & Development Operating System — inspired by the modular, self-contained nature of the jackfruit (*kathal* 🍈) itself. Just like the fruit, KATHAL OS is built from many independent "pods" — kernel, services, plugins, and applications — that work together as one cohesive system.

KATHAL OS is designed to be a maintainable, extensible, production-grade alternative to platforms like **Coolify**, **Dokploy**, **Portainer**, and **OpenPanel** — built from day one as if the repository will have thousands of stars and hundreds of contributors.

<div align="center">

| 🐳 Docker-native runtime | ☁️ Cloud & VPS management | 🤖 AI-powered automation |
|:---:|:---:|:---:|
| **🌐 Cloudflare integration** | **🔐 Security-first design** | **📊 Monitoring & Observability** |
| **🔌 Plugin ecosystem** | **⚡ Modern DX** | **🧩 Modular kernel** |

</div>

---

## 💡 Why KATHAL OS

> Built with a **development constitution**: production-grade only. No MVP shortcuts, no placeholders, no pseudo-code. Every phase treats the ones before it as an immutable contract.

- **Modular 4-layer kernel** — Kernel → Services → Plugin SDK → Applications, so the core stays small while capability grows through plugins.
- **AI-native from the ground up** — automation, diagnostics, and operational assistance are first-class citizens, not bolted on.
- **Inspired by, not copied from** — architectural DNA drawn from Docker, containerd, Traefik, Caddy, Dokploy, OpenPanel, Portainer, Grafana, Prometheus, Loki, Kubernetes, LiteLLM, and Next.js.
- **Scales down and up** — SQLite for single-node simplicity, PostgreSQL + Redis for multi-node scale.
- **Fully observable** — structured JSON logging, OpenTelemetry-compatible traces, and a Prometheus/Grafana/Loki/Alertmanager stack out of the box.

---

## 🏗️ Architecture

<div align="center">
  
<img width="2720" height="1600" alt="image" src="https://github.com/user-attachments/assets/78481adb-fa7c-48de-89fc-cc43a698fc78" />

</div>

KATHAL OS is built as a **Go workspace + pnpm workspace monorepo**, with project documentation kept living in `00_project/` (`Architecture.md`, `STATE.md`, `TODO.md`, `Roadmap.md`) so that any contributor — human or AI — can pick up development without replaying prior context.

---

## 📦 Projects

<div align="center">

| Project | Description |
|:---|:---|
| 🌳 **KATHAL OS** | Core Hosting & Development Operating System |
| ⌨️ **KATHAL CLI** | Command-line interface |
| ⚙️ **KATHAL Runtime** | Infrastructure runtime |
| 🤖 **KATHAL AI** | AI automation platform |
| 💿 **KATHAL Installer** | Windows / Linux installer |
| 🛒 **KATHAL Marketplace** | Plugins & templates |
| 🧰 **KATHAL SDK** | Plugin development kit |

</div>

---

## 🧱 Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Go-backend-00ADD8?style=flat-square&logo=go&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-frontend-black?style=flat-square&logo=next.js&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-frontend-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/TailwindCSS-styling-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white" />
<img src="https://img.shields.io/badge/shadcn%2Fui-components-000000?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/Docker-runtime-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Traefik-networking-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white" />
<img src="https://img.shields.io/badge/Cloudflare-tunnel-F38020?style=flat-square&logo=cloudflare&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/SQLite-single--node-003B57?style=flat-square&logo=sqlite&logoColor=white" />
<img src="https://img.shields.io/badge/PostgreSQL-multi--node-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-cache-DC382D?style=flat-square&logo=redis&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/Prometheus-metrics-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
<img src="https://img.shields.io/badge/Grafana-dashboards-F46800?style=flat-square&logo=grafana&logoColor=white" />
<img src="https://img.shields.io/badge/Loki-logs-F5A623?style=flat-square" />
<br/>
<img src="https://img.shields.io/badge/Python-AI%20runtime-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/LiteLLM-model%20routing-00b894?style=flat-square" />
<img src="https://img.shields.io/badge/MCP-compatible-6c5ce7?style=flat-square" />

</div>

| Layer | Technology |
|:---|:---|
| **Backend / Kernel** | Go |
| **Frontend** | Next.js, React, TypeScript, Tailwind, shadcn/ui |
| **CLI** | Go |
| **Container Runtime** | Docker Engine, Docker Compose |
| **Networking / Ingress** | Traefik, Cloudflare, Cloudflare Tunnel |
| **Data Layer** | SQLite (single-node) / PostgreSQL (multi-node) + Redis |
| **Observability** | Prometheus, Grafana, Loki, Alertmanager, OpenTelemetry |
| **AI Runtime** | Python, LiteLLM, OpenAI-compatible APIs, MCP *(Mojo/Rust reserved for later)* |
| **Installer** | Go + Bash |

---

## ⚡ Getting Started

> 🚧 KATHAL OS is under active development. Installation instructions will land here once an installable build is available.

```bash
# Coming soon
curl -fsSL https://your-domain.com/install.sh | bash
```

In the meantime, check the [Documentation](https://docs.your-domain.com) and [Discussions](../../discussions) to follow along with the build.

---

## 🗺️ Roadmap

KATHAL OS is being built in **20 planned phases**, one focused phase at a time — each phase treats everything before it as an immutable contract.

- [x] **Phase 1** — System Architecture
- [x] **Phase 2** — Repository Structure
- [ ] **Phase 3** — Technical Specifications
- [ ] **Phase 4** — Database Design
- [ ] **Phases 5–20** — Kernel, Services, Plugin SDK, AI Automation, Marketplace, Installer, and beyond

Track detailed progress in `00_project/STATE.md`, `00_project/TODO.md`, and `00_project/Roadmap.md`.

---

## 🤝 Contributing

KATHAL OS is being built in the open, for the community.

1. ⭐ Star the repository
2. 🍴 Fork and create a feature branch
3. 🛠️ Build against the current phase's architecture contract
4. 📬 Open a pull request

Contribution guidelines will be published in `CONTRIBUTING.md` as the project matures.

---

## 💬 Community

<div align="center">

<a href="#"><img src="https://img.shields.io/badge/Discord-Join%20Us-5865F2?style=for-the-badge&logo=discord&logoColor=white" /></a>
<a href="../../discussions"><img src="https://img.shields.io/badge/GitHub-Discussions-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

</div>

---

## ❤️ Built By

<div align="center">

### **BakeWeb**
in collaboration with
### **SunDial Technology**

</div>

---

<div align="center">

### 🌳 Open Source Forever

⭐ **Star** our repositories &nbsp;•&nbsp; 🍴 **Contribute** &nbsp;•&nbsp; 💚 **Build together**

<br/>

<sub>Made with 🌳 by the BakeWeb team</sub>

</div>
