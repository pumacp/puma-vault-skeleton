---
title: "Quartz Publishing"
jd: "00.11"
para: Meta
type: guide
tags: [guide, quartz, publishing, website]
---

# 🌐 Publishing with Quartz 4

This repository ships **no Quartz configuration** — Quartz is a separate tool you install only if you want a website. Keeping it out makes the skeleton tool-agnostic and avoids baking in anyone's personal paths or domain. This guide explains the setup in prose; you create the config from Quartz's own up-to-date defaults.

## What Quartz is
[Quartz 4](https://quartz.jzhao.xyz) (by **jackyzha0**) turns a folder of Markdown into a fast static website, preserving `[[wikilinks]]`, backlinks, and the graph view. Source: <https://github.com/jackyzha0/quartz>.

## Steps (about 15–20 minutes)
1. **Install prerequisites:** Node.js ≥ 20 and `git`.
2. **Get Quartz:**
   ```bash
   git clone https://github.com/jackyzha0/quartz.git
   cd quartz
   npm install
   ```
3. **Add your content:** copy this vault's Markdown into Quartz's `content/` folder (or point Quartz at this folder). Quartz treats `index.md` as the site landing page — this skeleton already provides one.
4. **Configure:** edit Quartz's own `quartz.config.ts` (created by Quartz, not shipped here) — set the site title to *PUMA Vault Skeleton*, your `baseUrl`, and your preferred theme. Follow the official guide: <https://quartz.jzhao.xyz/configuration>.
5. **Preview locally:**
   ```bash
   npx quartz build --serve
   ```
   Open <http://localhost:8080>.
6. **Deploy:** publish the generated `public/` directory to GitHub Pages, Netlify, Cloudflare Pages, or any static host. See <https://quartz.jzhao.xyz/hosting>.

## Notes
- Numeric, space-containing folder names (`40 - Projects`) render fine; Quartz slugifies them.
- Keep authoring in Obsidian; rebuild Quartz when you want to refresh the site.
- The `public/` build output is git-ignored in this repo by design.

## See also
[[Getting-Started]] · [[LLM Wiki]] · [[Diataxis]] · [[MOC Navigation]]
