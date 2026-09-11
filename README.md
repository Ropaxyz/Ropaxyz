# Ross Paxton

**ICT professional based in Ayrshire, Scotland.** I build Windows endpoint management tooling, self-hosted internal platforms, and small browser extensions that do one job properly.

---

## What I work on

- **Windows fleet management** — endpoint diagnostics, remediation, and audit tooling for machines at scale
- **Self-hosted platforms** — internal tools that replace rented SaaS (service desks, trackers, planners)
- **Assistive technology** — small utilities that make a screen easier to live with
- **Browser extensions** — narrow, single-purpose tools with no telemetry

---

## Featured projects

### [EaseView](https://github.com/Ropaxyz/EaseView) — Windows screen tint overlay

A click-through colour overlay that covers every monitor, built for reading comfort. Multi-monitor aware (recovers when displays come and go), DPI-aware, schedulable by fixed times or sunset-to-sunrise, with saved profiles, optional global hotkeys, portable mode, and a state-aware system tray UI.

`Python` · `Windows` · `assistive technology`

### [Octopus Agile Tracker](https://github.com/Ropaxyz/AgileTracker) — live electricity prices on a small display

Live Octopus Agile rates on a Waveshare **ESP32-C6 touch AMOLED**, with a Raspberry Pi + e-ink build as the legacy path. Shows the current rate, the next slot, a 48-slot day chart, and a run/wait score so you know when to switch something on. Flashes "PAID TO USE" when rates go negative.

`C++` · `ESP32` · `Arduino` · `e-ink`

### Browser extensions

| Extension | What it does | Browsers |
|---|---|---|
| [Save Image As PNG/JPG](https://github.com/Ropaxyz/Save-Image-As-PNG-JPG---Chrome-Edge) | Right-click any image to save it as PNG or JPG — no online converters. Uses an offscreen document to avoid tainted canvases. | Chrome, Edge |
| [Firefox Save As](https://github.com/Ropaxyz/Firefox_SaveAs) | The same idea for Firefox: PNG or JPG instead of WebP. | Firefox |
| [Amazon Bulk Cancel](https://github.com/Ropaxyz/SubscribeSaveBulkCancelChrome) | Cancel many Subscribe & Save items in one pass, with parallel workers, a live progress bar, retries and per-item timeouts. | Chrome, Edge |
| [Amazon Bulk Cancel for Firefox](https://github.com/Ropaxyz/FireFox-Bulk-Cancel-for-Amazon-Subscribe-Save) | The Firefox build of the same tool. | Firefox |
| [YouTube Shorts Auto-Next](https://github.com/Ropaxyz/FFyoutube-shorts-auto-next) | Automatically advances to the next Short. | Firefox |

All of these run entirely in the browser — nothing is sent anywhere.

---

## Also on GitHub

**[OctoBot](https://github.com/Ropaxyz/OctoBot-Octopus-Energy-Discord-Bot)** *(archived)* — a Python Discord bot that pulled Octopus Energy usage and cost data and charted it with matplotlib, over asyncio and GraphQL.

---

## Private & internal work

Some of my larger projects are private, because they're internal tools or they carry deployment detail. In short:

- **Aegis** — a Windows endpoint support and remediation console. Capability-aware connection routing (WinRM → CIM → WMI → SMB → SSH), a health dashboard, and one-click fixes that verify their own result and can roll back. Every action lands in an append-only audit trail with secrets redacted.
- **AyrDesk** — a self-hosted IT service desk: tickets, queues and routing, SLA tracking, asset register, knowledge base, and reporting.
- **Track Things** — a two-person diary PWA on Next.js and Supabase, where row-level security gates every record and photos are served behind an authenticated route.
- **LifeOS** — a self-hosted personal command centre (React, Express, Prisma, SQLite, Docker).
- **SAC_Printers / Printer_April** — printer management and reporting utilities.

---

## Tools I reach for

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C%2B%2B](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## Get in touch

I'm open to opportunities — the quickest way to reach me is here on GitHub, or open an issue on any project above.

<sub>Based in Ayrshire, Scotland · ICT at South Ayrshire Council</sub>
