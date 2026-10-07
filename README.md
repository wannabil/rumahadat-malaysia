# 🏡 Rumah Adat Malaysia

Explore traditional Malaysian houses in 3D: rotate, explode, cut open, and tap any part to learn what it does and what it means. Bilingual (BM / EN).

Made for **MalayaPulse** by **wanbl**.

**Live:** https://rumahadat-malaysia.wannabil-xyz.workers.dev

## Houses
- Rumah Kutai (Perak)
- Rumah Tiang Dua Belas (Kelantan & Terengganu)
- Rumah Melaka (Melaka)
- Rumah Bumbung Panjang (Negeri Sembilan)
- Rumah Limas (Johor)
- Rumah Panjang (Sarawak)

Deep-link a house with a hash, e.g. `/#melaka`, `/#n9`, `/#panjang`.

## Features
- Procedural 3D models (Three.js), no external model files
- Explode slider, cross-section cut, auto-spin, reset
- Tap/hover a part for its name and meaning
- Mobile-first, BM/EN toggle

## Stack
A single static `public/index.html` with Three.js from a CDN. It's served by Cloudflare Workers static assets.

```bash
npx wrangler dev      # local
npx wrangler deploy   # deploy
```

## Credits
The concept was inspired by [rumahadat.id](https://rumahadat.id) (Indonesian traditional houses in 3D). All code, models and text in this repo are original.

The 3D models are simplified illustrations, not architecturally exact.
