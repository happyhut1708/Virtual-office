# 🏢 Virtual Office — 3D Bot Team HQ

A **3D virtual office** for my AI bot team — one big bright floor rendered in
Three.js, with a presidential office for the boss. Open `index.html` in any
browser, no build step needed.

> **Showcase version — demo data.** All bot statuses, activities, and token
> numbers on this page are sample data for demonstration. The real live
> dashboard (with real-time data) is private.

## The office

One floor, four division zones, zero clicking between floors:

- 👑 **Presidential Office** — Agent M (the boss / front door of the team),
  big desk at the back of the room
- 💰 **Market & Crypto** — Crypto (👑 PRIORITAS), Stocks, Testnet
- 🔬 **Research & Planning** — Researcher, Planner
- 🎬 **Creative & Content** — Video Lab, Video Coding, Photo Editor, X Growth
- 💻 **Dev** — Websites, App Dev

## What's inside

- 🏢 **3D office scene** in Three.js: one bright daytime floor (blue sky,
  sun & clouds through the windows, cream walls, light wood floor, vivid
  pastel zone pads with zone signs)
- 🤖 **11 bot desks + presidential desk**, each with a 3D character:
  - ⌨️ typing animation = working
  - 💤 floating Zzz = chilling
  - 🕐 clock icon = scheduled
- 🖱️ **Hover / click any character or agent card** for a bot info popup
- 📊 **Tabs**: Token usage · Routing · Rules · Debug — plus a live WIB clock,
  a running team marquee, and a zone filter
- ✨ **Gen Z neo-brutalist style**: thick borders, hard shadows, bold pill
  tabs, sticker-style badges

## Deploy to Vercel (free)

1. This repo is already on GitHub 👋
2. Go to [vercel.com](https://vercel.com) → sign up with GitHub
3. **Add New → Project** → import `Virtual-office` → **Deploy**
4. Done — you get a public link like `virtual-office.vercel.app`

No build command, no framework — it's a single static `index.html`
(Three.js loads from CDN).

## Tech

- Single HTML file (HTML + CSS + JS), Three.js via CDN for the 3D scene
- Embedded demo data, works in any modern browser
- Mobile responsive, `prefers-reduced-motion` respected

---

*Built with [Muse](https://muse.ai) · Showcase/demo data — live version is private.*
