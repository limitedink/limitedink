<h1 align="center">Hi, I'm CJ 👋</h1>
<h3 align="center">Software developer in Melbourne building thoughtful systems, tools, and games.</h3>

<p align="center">
  Currently creating <strong><a href="https://github.com/limitedink/MOMENTUM">Momentum</a></strong>, a persistent multiplayer taskbar RPG built around always progressing together.
</p>

<p align="center">
  <a href="https://limitedink.github.io/MOMENTUM/"><strong>Play Momentum</strong></a> ·
  <a href="https://github.com/limitedink?tab=repositories">Projects</a> ·
  <a href="https://www.linkedin.com/in/christopher-james-santiago-limitedink/">LinkedIn</a> ·
  <a href="mailto:santiagochristopherjames1@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white" alt="Tauri" />
</p>

> I care about understanding how things work, designing systems that fit together cleanly, and turning ambitious ideas into working software one clear step at a time.

---

## What I'm building

### 🎮 [Momentum](https://github.com/limitedink/MOMENTUM)

**Momentum is the multiplayer taskbar RPG I wish existed.** It is designed to run quietly while players work, study, browse, or watch videos, while their characters continue training, gathering, crafting, fighting, and progressing alongside a party.

What began as an idle and active RPG prototype has grown into my first substantial end-to-end product:

- Built six connected skills, offline progression, upgrades, specializations, crafting, equipment, inventory, and loadouts
- Created active arena combat, progressive boss tiers, combat talents, run records, and an active Fishing minigame
- Designed a local asynchronous party expedition with shared activities, commands, snapshots, rewards, and reconnect behaviour
- Refactored the multiplayer client around authoritative snapshots, transport boundaries, session state, revision ordering, and pending command correlation
- Added a **Tauri 2** desktop shell for the future taskbar-native release
- Built a **TypeScript, Fastify, WebSocket, and PostgreSQL** backend foundation
- Implemented versioned SQL migrations, persistent players and sessions, hashed development tokens, bearer authentication, readiness checks, and PostgreSQL integration tests

The public prototype is playable now. Online multiplayer is still being built, but the client and backend foundations are being developed deliberately so the final social systems can be meaningful rather than superficial.

<p>
  <a href="https://limitedink.github.io/MOMENTUM/"><strong>▶ Play the prototype</strong></a>
  &nbsp;&nbsp;
  <a href="https://github.com/limitedink/MOMENTUM"><strong>View the repository</strong></a>
</p>

---

## Selected projects

These projects mark different stages of my growth as a developer:

| Project | What I built |
| --- | --- |
| **[Momentum](https://github.com/limitedink/MOMENTUM)** | A persistent idle and active RPG with a Tauri desktop shell, multiplayer-ready client architecture, Fastify backend, authentication, and PostgreSQL persistence. |
| **[Python Static Site Generator](https://github.com/limitedink/python-static-site-generator)** | A dependency-free Markdown-to-HTML generator with recursive page building, templates, asset copying, configurable base paths, and GitHub Pages deployment. [Live demo](https://limitedink.github.io/python-static-site-generator/) |
| **[Asteroids in Pygame](https://github.com/limitedink/asteroids-pygame)** | A real-time arcade game using object-oriented architecture, vector movement, projectile systems, collision detection, procedural spawning, and multi-stage asteroid splitting. |
| **[Colemak Mod-DH for ChromeOS](https://github.com/limitedink/Colemak-Mod-DH-Layout-for-Chromebooks-ChromeOS)** | A ChromeOS input-method extension that brings the Colemak Mod-DH keyboard layout to Chromebooks, including the on-screen keyboard. |
| **[TypeScript React Calculator](https://github.com/limitedink/TS-React-TailwindCSS-Calculator)** | A React and TypeScript calculator supporting arithmetic, modulus, powers, percentages, sign changes, decimal handling, and a responsive interface. [Live demo](https://limitedink.github.io/TS-React-TailwindCSS-Calculator/) |

---

## How I approach software

- **Start with the real problem.** I want to understand what a system is meant to accomplish before choosing patterns or tools.
- **Build in clear boundaries.** Small modules, explicit ownership, and understandable data flow make future complexity easier to handle.
- **Make progress visible.** I prefer small, meaningful iterations that leave the project better than I found it.
- **Test what matters.** Tests should protect behaviour and important boundaries, not exist only to increase a number.
- **Care about the experience.** Performance, reliability, game feel, interface clarity, and maintainability are all parts of the same product.
- **Keep learning honestly.** I do not need to pretend I know everything. I am good at digging into unfamiliar systems, asking why, and steadily turning confusion into understanding.

---

## About me

I have been drawn to computers for as long as I can remember. I built my first PC at around 11, started programming through C++ and small tools, then expanded into JavaScript, TypeScript, Python, Go, frontend development, backend systems, desktop applications, and game development.

At 13, I reached **Grandmaster in StarCraft II as Zerg**. More than the rank itself, I value what the process taught me: practise deliberately, review mistakes honestly, adapt quickly, and keep going when improvement is not immediately visible. That mindset still shapes the way I learn and build.

Today, most of my development energy goes into Momentum. It brings together the things I enjoy most: progression systems, game design, architecture, databases, networking, interfaces, and the challenge of turning a large idea into something real.

I am still early in my career, but I am not standing still. I have gone from small learning projects to designing and implementing a game client, desktop shell, multiplayer architecture, backend authentication, database migrations, persistent sessions, and tested PostgreSQL integration. **I am proud of that progress, and I am excited about how much further I can take it.**

---

## Tools and technologies

### Using in current projects

- **Languages:** TypeScript, JavaScript, Python, Go
- **Backend:** Node.js, Fastify, REST APIs, WebSockets, authentication and session systems
- **Data:** PostgreSQL, SQL migrations, SQLite
- **Frontend and desktop:** HTML, SCSS, Canvas API, Vite, Tauri 2
- **Testing:** Vitest, integration testing, testable architecture and dependency boundaries
- **Workflow:** Git, GitHub, npm, Linux, macOS

### Familiar with and continuing to develop

- React, Tailwind CSS, Express, Redis, Docker, GitHub Actions
- C++, C#, Godot, Unreal Engine 5, Unity
- Data structures, algorithms, API design, caching, observability, and deployment fundamentals

Tools are not the goal by themselves. I try to choose technology that helps me understand the problem, ship a useful result, and leave behind code I can continue improving.

---

## Learning

I use structured learning when it is useful, including the <a href="https://www.boot.dev/u/limitedink">Boot.dev backend path</a>, but I learn best by applying concepts directly inside real projects.

<p align="center">
  <a href="https://www.boot.dev/u/limitedink">
    <img src="https://api.boot.dev/v1/users/public/c5493f7f-d4a4-4c53-a026-4d60da616fb8/thumbnail" alt="CJ's Boot.dev profile" />
  </a>
</p>

---

## Beyond code

I love games with deep progression and strong systemic design, especially RPGs, strategy games, MMOs, and games that reward mastery over time. I also enjoy drumming, strength training, computer hardware, audio gear, ergonomic keyboard layouts, and spending far too long comparing mice, displays, and programming fonts.

I use **Colemak Mod-DH**, care more than most people about comfortable tools, and believe small improvements compound whether I am learning a song, refining a game system, or cleaning up an API.

---

## GitHub stats

<p align="center">
  <a href="https://github.com/limitedink">
    <img src="https://github-readme-stats.vercel.app/api?username=limitedink&show_icons=true&count_private=true&theme=midnight-purple" alt="CJ's GitHub stats" height="165" />
  </a>
  <a href="https://github.com/limitedink">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=limitedink&langs_count=7&layout=compact&theme=midnight-purple" alt="CJ's top languages" height="165" />
  </a>
</p>

---

## Contact

<p>
  <a href="mailto:santiagochristopherjames1@gmail.com">Email</a> ·
  <a href="https://www.linkedin.com/in/christopher-james-santiago-limitedink/">LinkedIn</a> ·
  Discord: <code>lilceej</code>
</p>
