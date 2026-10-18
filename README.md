# 🏢 Virtual Office — Pixel-Art Bot Team Dashboard

A **pixel-art virtual office** — a live-mirror style dashboard of my AI bot team,
rendered as a cozy top-down retro-game office scene. Open `index.html` in any
browser, no build step needed.

> **Showcase version — demo data.** All bot statuses, activities, and token
> numbers on this page are sample data for demonstration. The real live
> dashboard (with real-time data) is private.

## What's inside

- 🌃 **Pixel-art office scene** drawn purely in code (canvas, zero external assets):
  night-time cozy room with starry windows + moon, real-time wall clock,
  hanging lamps, carpet, and a coffee corner
- 🤖 **9 bot desks** — Aman (👑 PRIORITAS), Bursa, Klip, Uji, Cuit, Laman,
  Jepret, Loot, Gali — each with a name plate and a live sprite:
  - ⌨️ typing animation + green code screen = working
  - 💤 floating Zzz = chilling
  - 🕐 spinning clock bubble = scheduled
- 🖱️ **Hover / click any sprite** for a bot info popup
  (name, lane, status badge, last activity, data timestamp)
- 📑 **5 tabs**: Office · Token usage · Routing · Aturan · Debug
  (routing plan, lane rules, office rules, live activity feed, WIB clock)
- ✨ Animations: staggered card entrances, hover glow, count-up stats,
  pulsing status dots, ambient canvas particles, scroll reveals

## Deploy to Vercel (free)

1. Push this repo to GitHub (already here 👋)
2. Go to [vercel.com](https://vercel.com) → sign up with GitHub
3. **Add New → Project** → import `virtual-office` → **Deploy**
4. Done — you get a public link like `virtual-office.vercel.app`

No build command, no framework — it's a single static `index.html`.

## Tech

- Single self-contained HTML file (HTML + CSS + JS + canvas)
- No dependencies, no external assets, works offline
- Light/dark theme aware, mobile responsive,
  `prefers-reduced-motion` respected

---

*Built with [Muse](https://muse.ai) · Showcase/demo data — live version is private.*
