# Hi, I'm Francesco

I'm a 17-year-old Full-Stack AI Engineer from Italy. I build web products, local-first AI tools, and hardware-to-software systems, taking them from interface to deployment since 2024. I also build the tools that shape how I work: Traflix Voice captures intent, while Traflix Space keeps projects, terminals, and coding agents together.

## Start Here

- [DJI RC-N1C Flight Deck](https://github.com/iTzFrancesco/dji-rcn1c-flight-deck): open-source bridge that lets a real DJI RC-N1C remote control PC and Android flight simulators over USB or Wi-Fi.
- [Traflix Voice](https://github.com/iTzFrancesco/Traflix-Voice): open-source desktop dictation that turns spoken ideas into text inside the active app, with a local-first path and automatic paste.
- [Traflix Space](https://github.com/iTzFrancesco/Traflix-Space): open-source Windows workspace for coordinating multiple projects, live agent sessions, and workspace-aware Jarvis.
- [GigaMC](https://gigamc2.netlify.app): full-stack community operations platform for tournaments, forums, staff workflows, and administration.

## What I build

I build products that turn messy workflows into focused tools. My AI work stays close to the user's task: Voice captures intent, Space provides project context and lets me run different agents side by side, and tests and runtime checks decide what ships. The same approach extends to community operations, hardware interfaces, and other projects: use the right tool for a focused pass, keep boundaries clear, and verify the result.

## AI workflow

I use AI as part of an engineering loop, not as a replacement for engineering judgment:

1. **Capture intent:** Traflix Voice turns an idea, bug, or next action into text inside the active tool. Local Whisper is the default; Groq is an explicit cloud option when speed matters.
2. **Keep context together:** Traflix Space keeps the repository, real terminals, files, and screenshots in one workspace. Jarvis adds workspace-aware context and controlled actions through the Codex App Server.
3. **Run focused passes:** Codex, Claude Code, OpenCode, Pi, and other agents get bounded roles such as exploring, implementing, reviewing, or diagnosing.
4. **Verify the change:** I close the loop with targeted tests, lint/build, browser checks, and a review of the actual diff.

## Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![Tauri](https://img.shields.io/badge/Tauri-FFC131?style=flat-square&logo=tauri&logoColor=black) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Codex](https://img.shields.io/badge/Codex-000000?style=flat-square&logo=openai&logoColor=white)

## Selected work

### [DJI RC-N1C Flight Deck](https://github.com/iTzFrancesco/dji-rcn1c-flight-deck)

An open-source bridge that lets a real DJI RC-N1C remote control PC and Android flight simulators instead of staying locked to the DJI ecosystem. It carries physical sticks and buttons across USB or Wi-Fi, translates them into simulator input, and exposes connection and signal state through a local dashboard. Stack: Python, USB/VCOM, UDP/Wi-Fi, and ViGEmBus.

### [Traflix Voice](https://github.com/iTzFrancesco/Traflix-Voice)

An open-source desktop dictation tool that turns spoken ideas into text inside the app I am already using. Its special part is the local-first experience: global hotkeys, automatic paste, and repeated latency and reliability work around recording, transcription, and provider switching. The project benchmark measures the local stop-to-request path at 0.179 ms median / 0.303 ms p95; full inference varies with the selected model and provider. Stack: Tauri/Rust, React/TypeScript, Python, Whisper.cpp, and Groq.

### [Traflix Space](https://github.com/iTzFrancesco/Traflix-Space)

An open-source Windows workspace for coordinating development across projects and agents. I use it as a control room: keep multiple workspaces and live terminal sessions available, run different coding agents side by side, and give each one a focused role instead of mixing every task into one chat. Jarvis adds workspace-aware context and controlled actions through the Codex App Server. Stack: React/TypeScript, Tauri/Rust, ConPTY, and xterm.js.

### [GigaMC](https://gigamc2.netlify.app)

A full-stack community platform that turns tournament, staff, and forum work into one operational system for a gaming community. It gives members one place to participate and gives staff the tools to manage applications, events, and day-to-day moderation through Discord sign-in and an admin panel. Stack: React/TypeScript, Node.js, Supabase/PostgreSQL, and Discord OAuth.

## Collaboration

I'm open to open-source collaborations, developer tools, and practical AI projects with people who care about shipping reliable software.

**Working on something interesting? Get in touch.**

[Portfolio](https://traflix.dev) · [GitHub](https://github.com/iTzFrancesco) · [Email](mailto:francesco@traflix.dev) · [Discord](https://discord.com/users/811969190742327326)
