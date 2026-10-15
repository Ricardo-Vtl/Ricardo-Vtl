<!--
  ==========================================================================
  LINKS — single source of truth (reference-style definitions live at the
  bottom of this file, just before the closing comment). If a URL changes,
  update the definition there once and every link follows.

  portfolio : https://rvital.dev
  rms repo  : https://github.com/Ricardo-Vtl/Restaurant-Management-System-RMS-Demo
  rms demo  : https://rms.rvital.dev
  deckcraft : https://github.com/Ricardo-Vtl/DeckCraft
  linkedin  : https://www.linkedin.com/in/ricardo-vital-dev
  email     : vitalnegretericardo@gmail.com

  ASSETS (all live in assets/, SVG, scale via width="100%"):
    banner.svg       1200x300  bg #0a0a0a, accent #ff6b35, terminal mockup
    divider.svg      1200x16   accent #ff6b35 glow line (1192x10, r5)
    footer-mark.svg  1200x80   wordmark #ff6b35 + #8a8a8a
  Every "---" between sections is the divider; footer-mark sits above the
  "Open to work" line.

  ANALYTICS — services + palette (bg 0a0a0a · accent ff6b35 · text c9d1d9 ·
  muted 8a8a8a · line 30363d/1c2128). All best-effort public instances:
    stats / top-langs : https://github-readme-stats.vercel.app/api
    streak            : https://streak-stats.demolab.com  (was herokuapp, dead)
    activity graph    : https://fabianocouto-activity-graph.vercel.app/graph
                        (upstream vercel paused/billing-locked -> community mirror)
  ==========================================================================
-->

<p align="center">
  <img src="assets/banner.svg" alt="Ricardo Vital — Full-Stack Developer" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ricardo-vital-dev"><img src="https://img.shields.io/badge/LinkedIn-555555?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://rvital.dev"><img src="https://img.shields.io/badge/Portfolio-ff6b35?style=flat&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:vitalnegretericardo@gmail.com"><img src="https://img.shields.io/badge/Email-555555?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## About

Self-taught full-stack developer, building complete web products end to end since August 2024 — requirements, architecture, code, security, deploy, docs. I paused a 10-semester Computer Systems Engineering program (TecNM) to learn by shipping real software instead; training as a Mechatronics technician is where the hardware-and-code habit started.

I care more about solid engineering underneath than about what merely looks good — I adopt new tools only when they bring real gains in performance, maintainability and developer experience.

**Now:** RMS is live (demo below) and still evolving, alongside my bilingual (EN/ES) portfolio site.

On-site in Irapuato, Mexico · full remote elsewhere · available immediately.

<p align="center">
  <img src="assets/divider.svg" alt="" width="100%" />
</p>

## Featured projects

### [Restaurant Management System (RMS)][repo]
White-label restaurant management platform, built and shipped end to end: public landing with a live digital menu and online ordering — plus a 9-module panel (Dashboard, Tables, Orders, Kitchen KDS, Cashier, Menu, Inventory, Staff, Settings). API-only writes with atomic PostgreSQL RPCs, row-level security, Zod validation at every boundary, real-time sync and rate limiting.

Client read-only over RLS + Realtime · service-role Route Handlers · SQL migrations · Vitest suite · full technical documentation. 36 commits, feature-based clean architecture.

**Stack:** Next.js 16 · React 19 · TypeScript (strict) · Supabase (PostgreSQL, Auth, Realtime) · TanStack Query · Tailwind CSS v4 · shadcn/ui · Zustand · Zod · Upstash Redis · Vitest · Vercel

[Repo][repo] · [Live demo][demo]

### [DeckCraft][deckcraft]
Ultra-lightweight open-source Stream Deck alternative for DIY hardware: detects Arduino-compatible boards over Serial and HID, maps physical buttons to keyboard shortcuts, app launches, macros and a virtual-microphone soundboard — with profiles and a drag-and-drop canvas.

**Stack:** Tauri v2 (Rust) · React 19 · TypeScript · hidapi · MIT licensed

### [Portfolio][portfolio]
Bilingual (EN/ES) portfolio — dark technical-minimal design with a cinematic depth system (Lenis smooth scroll + GSAP + a WebGL field), custom motion architecture, and SEO/structured data and accessibility as first-class constraints.

**Stack:** Next.js 16 · React 19 · TypeScript · Tailwind CSS v4 · GSAP + Motion · Lenis · OGL (WebGL)

<p align="center">
  <img src="assets/divider.svg" alt="" width="100%" />
</p>

## How I work

Good software comes from deliberate decisions — architecture first, then code, verified at every step.

| | |
|---|---|
| `rv.plan` | Requirements first, architecture second, code last. If the problem isn't clear, nothing gets built. |
| `rv.build` | I turn the plan into working code step by step, keeping every decision explicit and reversible. |
| `rv.verify` | Output is a draft until tests, review and security checks pass. Nothing ships unverified. |
| `rv.ship` | Deploy, document the decisions, leave the system maintainable. Software that can't be maintained isn't finished. |

<p align="center">
  <img src="assets/divider.svg" alt="" width="100%" />
</p>

## Stack

**Languages** — TypeScript · JavaScript · SQL · Node.js · Python (basic) · C# (basic)

**Frontend** — React 19 · Next.js 16 · Tailwind CSS v4 · shadcn/ui · TanStack Query · Zod · Framer Motion / Motion

**Data** — PostgreSQL · Supabase (RLS, migrations, realtime) · MySQL (basic) · Upstash Redis

**Tooling** — Git & GitHub (conventional commits) · Vercel · pnpm · Vitest · REST API integration

**Also** — PC, laptop and smartphone hardware repair · Spanish (native) · English (B1)

<p align="center">
  <img src="assets/divider.svg" alt="" width="100%" />
</p>

## GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ricardo-Vtl&show_icons=true&hide_border=true&bg_color=0a0a0a&title_color=ff6b35&icon_color=ff6b35&text_color=c9d1d9&hide_rank=true&cache_seconds=86400" alt="GitHub stats for Ricardo-Vtl" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ricardo-Vtl&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=ff6b35&text_color=c9d1d9&langs_count=6" alt="Top languages for Ricardo-Vtl" width="48%" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Ricardo-Vtl&hide_border=true&background=0a0a0a&border=30363d&stroke=30363d&ring=ff6b35&fire=ff6b35&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=ff6b35&sideLabels=c9d1d9&dates=8a8a8a" alt="GitHub streak for Ricardo-Vtl" width="100%" />
</p>

<p align="center">
  <img src="https://fabianocouto-activity-graph.vercel.app/graph/?username=Ricardo-Vtl&bg_color=0a0a0a&color=c9d1d9&title_color=ff6b35&line=ff6b35&point=c9d1d9&area=true&area_color=ff6b35&hide_border=true&radius=8&days=31" alt="Contribution activity for Ricardo-Vtl" width="100%" />
</p>

<p align="center">
  <img src="assets/divider.svg" alt="" width="100%" />
</p>

<p align="center">
  <img src="assets/footer-mark.svg" alt="Ricardo Vital" width="100%" />
</p>

<p align="center">
  <sub>Open to work — full-time or contract. <a href="mailto:vitalnegretericardo@gmail.com">vitalnegretericardo@gmail.com</a></sub>
</p>

[repo]: https://github.com/Ricardo-Vtl/Restaurant-Management-System-RMS-Demo
[demo]: https://rms.rvital.dev
[deckcraft]: https://github.com/Ricardo-Vtl/DeckCraft
[portfolio]: https://rvital.dev
