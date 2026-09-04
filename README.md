# 🔦 Shadow Hunters

**Chasing shade, mapping heat** — a phygital campaign by students of Liceo Scientifico Statale “Aristotele” (Rome) for the Erasmus+ contest *“Rotte sostenibili: Green Finland”*.

*Se tre alberi hanno cambiato una strada, una mappa può cambiare una città.* / *If three trees changed a street, a map can change a city.*

Students map Rome's **heat islands** (🔴 unbearable places) and **cool islands** (🔵 shade refuges, like the three walnut trees of the project) on an open-source map, publish the data on the school's social channels, and challenge the Municipality and the school to plant trees and create shade.

## 🌍 Language
Interface available in **Italiano · English · Suomi** (dropdown in the top-right corner). The choice is remembered on your device.

## ✨ Features
- Live map (Leaflet + OpenStreetMap), optimized for PC, iOS and Android
- One-tap city switch: **Rome – Liceo Aristotele** ↔ **Helsinki – Etu-Töölö**
- Add a point with **preview + confirmation** (no accidental markers)
- Optional **note** (280 chars) and **1–5 star rating** per point
- Local point counter
- **Export CSV** for the Municipality: `Type, Latitude, Longitude, Timestamp, Note, Rating`
  - Desktop: automatic download
  - iOS / Android: system share sheet → “Save to Files” (plus a 📋 Copy fallback button)
- Remove single points (from their popup) or clear the whole map

## 🚀 How to run
The app is a single static file — no build, no server needed.

1. Open `index.html` in any modern browser (internet connection required for the CDN map tiles).
2. Or publish it on **GitHub Pages** (recommended — works perfectly on iPhone):
   - create a public repository named e.g. `shadow-hunters`;
   - upload `index.html` (and this `README.md`);
   - Settings → Pages → Branch: `main` → Save;
   - after ~1 minute the app is live at `https://<your-username>.github.io/shadow-hunters/`.

## 📁 Files
| File | Purpose |
|------|---------|
| `index.html` | The whole app (HTML + CSS + JS, i18n IT/EN/FI built in) |
| `README.md` | This page |

## 🧰 Built with (all free / open source)
- [Leaflet](https://leafletjs.com/) + [OpenStreetMap](https://www.openstreetmap.org/) tiles
- [Tailwind CSS](https://tailwindcss.com/) (CDN)
- Vanilla JavaScript — data stays on the device; nothing is uploaded

## 🎓 Project context
Erasmus+ school contest **“Rotte sostenibili: Green Finland”** — Liceo Scientifico Statale “Aristotele”, Rome (Italy), A.Y. 2026/27. Partner school: Etu-Töölö Upper Secondary School, Helsinki.
