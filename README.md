<div align="center">

# Aleksey Ermakov

**TypeScript developer building maintainable backend, desktop, and web products.**

<a href="https://t.me/realfamousbae"><img src="https://img.shields.io/badge/Telegram-@realfamousbae-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" /></a>
<img src="https://img.shields.io/badge/Location-Moscow-555?style=flat-square&logo=googlemaps&logoColor=white" alt="Moscow" />

English · [Русский](README.ru.md)

</div>

---

## About

I build products end to end: typed APIs and data layers, cross-platform desktop apps, mobile clients, and the web frontends that tie them together. I care about predictable architecture, reproducible setups, and honest documentation. Each project below is public, and its README describes how to run it.

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

### [Veil](https://github.com/realfamousbae/Veil)

A private world map on OpenStreetMap with no accounts, cookies, or analytics. It is a static site with no backend: vector maps, place search, offline regions, saved places that stay on the device, and an installable PWA with light, dark, and paper themes. The privacy rules are written down as a contract and checked by an automated test in CI on every change.

`Svelte` · `MapLibre` · `PMTiles` · `TypeScript` · `PWA`

→ [Open the map](https://veil-239.pages.dev)

### [Limita](https://github.com/realfamousbae/limita)

A native menu-bar and tray app for macOS and Windows that shows Claude Code and Codex rate limits at a glance. A hover pill slides in at the top edge of any screen, and the dashboard shows 5-hour and weekly limits, countdowns to each reset, balances, and the reason whenever a live update fails. The macOS app is written in Swift. Version 0.3 adds a Windows port built with Tauri and Rust. Limita reads credentials but never stores or refreshes them.

`Swift` · `SwiftUI` · `Rust` · `Tauri` · `TypeScript`

→ [Download for macOS or Windows](https://github.com/realfamousbae/limita/releases)

### [realfamousbae focus](https://github.com/realfamousbae/realfamousbae-focus)

Private countdown timers that sync across devices. Timers are scoped to the signed-in user and stored in Cloudflare D1. The app imports `.ics`/`.ical` and Google Calendar `.csv` files and handles recurring events, exclusions, duplicates, and time zones. The interface is available in English and Russian.

`Next.js 16` · `React 19` · `TypeScript` · `Cloudflare Workers & D1` · `Drizzle ORM` · `Vite`

→ [Live website](https://focus.realfam0usbae.chatgpt.site)

### [Staya](https://github.com/realfamousbae/Staya)

An open-source iOS and Android app for sharing location with a small circle of friends. Coordinates are end-to-end encrypted on the device with Olm/Megolm, and the server stores only the ciphertext of the latest packet. There is no phone number, no email, and no movement history. Early development: not usable yet.

`Rust` · `Swift` · `SwiftUI` · `Kotlin` · `PostgreSQL`

### [Data Expedition](https://github.com/realfamousbae/data-expedition)

A Claude Code plugin and skill for deep investigation. It makes Claude work like a careful investigator instead of a fast summarizer: it analyzes repositories, researches the web across primary sources, and verifies claims before writing an evidence-backed report. It targets Claude Opus and Fable class models.

`Claude Code plugin` · `Python` · `Markdown`

### [RFB Jukebox](https://github.com/realfamousbae/drg-rfb-jukebox-music)

A Deep Rock Galactic mod that replaces all Space Rig jukebox songs with 39 custom tracks. It ships audio assets only, runs client-side, and fits every track to the exact duration the game allots to its slot.

`Python` · `PowerShell` · `Unreal Engine 4.27`

→ [Releases](https://github.com/realfamousbae/drg-rfb-jukebox-music/releases)

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
