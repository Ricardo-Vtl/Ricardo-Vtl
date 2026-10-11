<!--
  ==========================================================================
  LINKS — single source of truth (reference-style definitions live at the
  bottom of this file, just before the closing comment). If a URL changes,
  update the definition there once and every link follows.

  portfolio : https://ricardo-vital.vercel.app
  pos repo  : https://github.com/Ricardo-Vtl/restaurant-pos-webapp
  pos demo  : https://restaurant-pos-webapp.vercel.app
  deckcraft : https://github.com/Ricardo-Vtl/DeckCraft
  linkedin  : https://www.linkedin.com/in/ricardo-vital-dev
  email     : vitalnegretericardo@gmail.com

  ASSETS (Figma) — export to assets/ in this repo:
    banner.svg     1200x300  bg #0d1117, accent #ff6b35, mono labels  [required]
    divider.svg    1200x16   1px line #1c2128 + 24px tick #ff6b35    [optional]
    footer-mark.svg 1200x80  footer mark                              [optional]
  To use the optional divider, replace the "---" between sections below.
  ==========================================================================
-->

<p align="center">
  <img src="assets/banner.svg" alt="Ricardo Vital — Full-Stack Developer" width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/ricardo-vital-dev"><img src="https://img.shields.io/badge/LinkedIn-555555?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://ricardo-vital.vercel.app"><img src="https://img.shields.io/badge/Portfolio-ff6b35?style=flat&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:vitalnegretericardo@gmail.com"><img src="https://img.shields.io/badge/Email-555555?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

## About

Self-taught full-stack developer, one year into building complete web products end to end — requirements, architecture, code, security, deploy, docs. I paused a 10-semester Computer Systems Engineering program to learn by shipping real software instead; training as a Mechatronics technician is where the hardware-and-code habit started.

I work with AI agents as leverage under my direction, never as an oracle: output stays a draft until tests, review and security checks pass.

**Now:** finalizing a public white-label release of the POS platform below, plus a bilingual (EN/ES) portfolio site.

On-site in Irapuato, Mexico · full remote elsewhere · available immediately.

---

## Featured projects

### [Restaurant POS WebApp][repo]
White-label point-of-sale and management platform, built and shipped end to end: public storefront with digital menu, product configurator and cart — plus a 9-module admin panel (Dashboard, Tables, Orders, Kitchen KDS, Cashier, Menu, Logistics, Staff, Settings) with staff roles and permissions.

REST APIs · row-level security · rate limiting · real-time orders and kitchen · SQL migrations · automated tests · full technical documentation. 132 commits, feature-based clean architecture.

**Stack:** Next.js 16 · React 19 · TypeScript (strict) · Supabase (PostgreSQL) · Tailwind CSS v4 · Upstash Redis · Zustand · Vitest · Vercel

[Repo][repo] · [Live demo][demo]

### [DeckCraft][deckcraft]
Ultra-lightweight open-source Stream Deck alternative for DIY hardware: detects Arduino-compatible boards over Serial and HID, maps physical buttons to keyboard shortcuts, app launches, macros and a virtual-microphone soundboard — with profiles and a drag-and-drop canvas.

**Stack:** Tauri v2 (Rust) · React 19 · TypeScript · hidapi · MIT licensed

### [Portfolio][portfolio]
Bilingual (EN/ES) portfolio — dark technical-minimal design, motion architecture, SEO and accessibility as first-class constraints.

**Stack:** Next.js 16 · Tailwind CSS v4 · GSAP + Motion · TypeScript

---

## How I work

AI is my tool, not my replacement: I set the architecture and I verify everything.

| | |
|---|---|
| `rv.plan` | Requirements first, architecture second, code last. If the problem isn't clear, nothing gets built. |
| `rv.build` | Build with leverage — I orchestrate AI agents and CLI/MCP tooling from the terminal. They never receive secrets or sensitive data. |
| `rv.verify` | AI output is a draft until tests, code review and security checks pass. Nothing ships unverified. |
| `rv.ship` | Deploy, document the decisions, leave the system maintainable. Software that can't be maintained isn't finished. |

---

## Stack

**Languages** — TypeScript · JavaScript · SQL · C# (basic)

**Frontend** — React 19 · Next.js 16 · Tailwind CSS v4 · shadcn/ui · Framer Motion / Motion

**Data** — PostgreSQL · Supabase (RLS, migrations, realtime) · MySQL (basic) · Upstash Redis

**Tooling** — Git & GitHub (conventional commits) · Vercel · pnpm · Vitest · REST API integration

**Also** — PC, laptop and smartphone hardware repair · Spanish (native) · English (B1)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Ricardo-Vtl&show_icons=true&hide_border=true&bg_color=0d1117&title_color=ff6b35&icon_color=ff6b35&text_color=c9d1d9&hide_rank=true&cache_seconds=86400" alt="GitHub stats for Ricardo-Vtl" width="48%" />
</p>

---

<p align="center">
  <sub>Open to work — full-time or contract. <a href="mailto:vitalnegretericardo@gmail.com">vitalnegretericardo@gmail.com</a></sub>
</p>

[repo]: https://github.com/Ricardo-Vtl/restaurant-pos-webapp
[demo]: https://restaurant-pos-webapp.vercel.app
[deckcraft]: https://github.com/Ricardo-Vtl/DeckCraft
[portfolio]: https://ricardo-vital.vercel.app
