<div align="center">

# Aleksey Ermakov

**TypeScript developer building maintainable backend, desktop, and web products.**

<a href="https://t.me/realfamousbae"><img src="https://img.shields.io/badge/Telegram-@realfamousbae-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" /></a>
<img src="https://img.shields.io/badge/Location-Moscow-555?style=flat-square&logo=googlemaps&logoColor=white" alt="Moscow" />

English · [Русский](README.ru.md)

</div>

---

## About

I build products end to end: typed APIs and data layers, cross-platform desktop apps, mobile clients, and the web frontends that tie them together. I care about predictable architecture, reproducible setups, and honest documentation. Each project below can be cloned and run as its README describes.

## Tech stack

<h4 align="center">Languages</h4>

<p align="center">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust" />
<img src="https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white" alt="Swift" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
</p>

<h4 align="center">Backend</h4>

<p align="center">
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS" />
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
<img src="https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" alt="GraphQL" />
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
<img src="https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black" alt="Drizzle" />
</p>

<h4 align="center">Frontend, mobile & desktop</h4>

<p align="center">
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
<img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
<img src="https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white" alt="Tauri" />
<img src="https://img.shields.io/badge/SwiftUI-0D96F6?style=flat-square&logo=swift&logoColor=white" alt="SwiftUI" />
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
</p>

<h4 align="center">Data & infrastructure</h4>

<p align="center">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/CockroachDB-6933FF?style=flat-square&logo=cockroachlabs&logoColor=white" alt="CockroachDB" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflareworkers&logoColor=white" alt="Cloudflare Workers" />
<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

## Featured projects

### [realfamousbae focus](https://github.com/realfamousbae/realfamousbae-focus)

Private countdown timers that sync across devices. Timers are scoped to the signed-in user and stored in Cloudflare D1. The app imports `.ics`/`.ical` and Google Calendar `.csv` files and handles recurring events, exclusions, duplicates, and time zones. The interface is available in English and Russian.

`Next.js 16` · `React 19` · `TypeScript` · `Cloudflare Workers & D1` · `Drizzle ORM` · `Vite`

→ [Live website](https://focus.realfam0usbae.chatgpt.site)

### [Limita](https://github.com/realfamousbae/limita)

A native macOS menu-bar app that shows Claude Code and Codex rate limits at a glance. A hover pill slides in at the top edge of any screen, away from the notch. Each service is polled live on its own schedule, and the dashboard marks stale data and shows readable errors. It reads credentials from the Keychain without ever refreshing or modifying them.

`Swift` · `SwiftUI` · `Keychain`

→ [Download DMG](https://github.com/realfamousbae/limita/releases)

### [Developer Profile API](https://github.com/realfamousbae/developer-profile-api)

A production-style, read-only GraphQL service built with NestJS. Prisma owns the persistence layer over CockroachDB. A single `docker compose up` starts the database, waits for it to be healthy, applies migrations, runs an idempotent seed, and then starts the API.

`NestJS` · `GraphQL (Apollo)` · `Prisma` · `CockroachDB` · `Docker`

### [My Staff](https://github.com/realfamousbae/my-staff)

A local-first Android app for collectors that turns photos of physical items into personal collectible cards. The original photos and SQLite data stay on the device. Sync goes through an account on your own NestJS + PostgreSQL backend, and backups export as portable ZIP archives. The data model keeps personal items separate from catalog editions.

`React Native` · `Expo` · `TypeScript` · `SQLite` · `NestJS` · `PostgreSQL`

→ [Try the APK](https://github.com/realfamousbae/my-staff/releases)

### [Hubble](https://github.com/realfamousbae/hubble)

A cross-platform workspace that runs web services (Telegram, YouTube, Discord, music, AI tools) as native tiles in one window. Version 1.0 is a full rewrite from Electron to Tauri 2 that uses the system webview instead of a bundled Chromium. It features BSP auto-tiling, isolated persistent sessions for each service, and media controls. Remote pages get no native IPC access.

`Tauri 2` · `Rust` · `TypeScript` · `React`

## GitHub activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-summary-card-output/github_dark/1-repos-per-language.svg" />
  <img src="./profile-summary-card-output/github/1-repos-per-language.svg" alt="Repositories per language" width="49%" />
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-summary-card-output/github_dark/4-productive-time.svg" />
  <img src="./profile-summary-card-output/github/4-productive-time.svg" alt="Productive time" width="49%" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=realfamousbae&theme=github-dark-blue&hide_border=true" />
  <img src="https://streak-stats.demolab.com?user=realfamousbae&theme=default&hide_border=true" alt="GitHub streak" />
</picture>

</div>
