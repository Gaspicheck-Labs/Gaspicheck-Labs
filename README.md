# 🌿 GasPi-Check

![Version](https://img.shields.io/badge/version-9.5.5-4CAF50?style=flat-square)
![Platform](https://img.shields.io/badge/platform-Android%20%7C%20iOS-blue?style=flat-square)
![Stack](https://img.shields.io/badge/stack-React%20Native%20%2F%20Expo%20%2F%20TypeScript-orange?style=flat-square)
![Architecture](https://img.shields.io/badge/architecture-Local%20First%20Cloud%20Sync-purple?style=flat-square)
![License](https://img.shields.io/badge/license-Proprietary-red?style=flat-square)
![Commits](https://img.shields.io/badge/commits-280+-lightgrey?style=flat-square)

> Every gram of food saved is a gram of CO₂ that never existed.
> GasPi-Check turns your fridge into a behavioral data engine — and makes sustainability a multiplayer game.

**🌐 [gaspicheck.com](https://gaspicheck.com) · 📧 [contact@gaspicheck.com](mailto:contact@gaspicheck.com)**

---

## 📱 The app

| Login | Product Scanner | My Fridge |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/a79fcb8a-c4e3-42f8-8f78-b8ecf5a8cb50" width="220"/> | <img src="https://github.com/user-attachments/assets/eb6b6485-be70-4a44-a56c-548092bf4e2b" width="220"/> | <img src="https://github.com/user-attachments/assets/c4241179-694a-4db6-ab60-9ed519d907b9" width="220"/> |

&nbsp;

| Personal Statistics | Shared Family Fridge | Live Community Stats |
| :---: | :---: | :---: |
| <img src="https://github.com/user-attachments/assets/4e9402a0-4751-4c9d-bd40-274ce84f5ba3" width="220"/> | <img src="https://github.com/user-attachments/assets/77d47d61-9c89-4591-a45e-32d252bbd0d7" width="220"/> | <img src="https://github.com/user-attachments/assets/e8b96b15-3faa-4c69-a65a-16a20712f3cf" width="220"/> |

---

## 🚀 What it does

GasPi-Check is a **React Native app** that tracks household food consumption in real time, scores eco-responsible behavior, and aggregates anonymous waste data at scale.

Not a reminder app. Not a shopping list.
A **behavioral change engine** — with hardcore gamification, family sync, and a data pipeline that no market research firm can replicate.

---

## 🎮 Hardcore gamification

10 prestige grades. Real effort economy. No XP for buying — only for acting responsibly.

| Action | XP |
|---|---|
| Consume a green product before expiry | +50 XP |
| Consume an orange product | +20 XP |
| Voluntary waste (with confirmation) | −200 XP |
| Automatic expiry penalty | −100 XP |

10 grades from **"Stock Novice"** to **"Eternal Legion"** · Power Cards · ×1.5 streak multiplier · 12 monthly Eco-Legacy challenges · Family XP shared in real time

---

## 🚀 Core features

### 🏗️ Local First architecture
Every write hits AsyncStorage first — zero perceived latency. Full offline mode, auto-sync on reconnect. Inspired by Notion, Linear, Figma.

### 👨‍👩‍👧 Family fridge sync
Real-time inventory sharing across up to 6 members via Firestore onSnapshot. "Added by [name]" on every food card. Shared family XP.

### 🔐 Privacy-first · GDPR
Rotating anonymous IDs every 28 days. Zero GPS, zero email in analytics. One-tap full data wipe — cloud + local. GDPR Art. 17 compliant.

### 🌱 CO₂ engine — Agribalyse
Hybrid model: Agribalyse data per product when available, per-category fallback. Every action increments a scientifically-grounded CO₂ counter.

### 📊 BigQuery analytics pipeline
3 Firebase→BigQuery extensions. 37-column analytics view. Weekly + monthly snapshots. GDPR TTL enforced at 24 months automatically.

### 🔔 Smart notifications
J-1 and J-0 expiry alerts per product. Monday recap every week. Android priority MAX channel. Hash guard prevents duplicates.

---

## 💰 The data moat

GasPi-Check captures what no company can buy elsewhere — **real behavioral data on food waste, at the exact moment it happens, inside real fridges.**

Nielsen and Kantar run panels of 2,000 people max, with declarative data.
GasPi-Check is behavioral, real-scale, EAN-level, timestamped.

| Metric | At 5,000 active users |
|---|---|
| Events / month | ~780,000 |
| Dimensions per event | 37 |
| One-shot brand report | €20K – €300K |
| Annual monitoring deal | up to €500K |
| Target clients | Danone · Nestlé · Carrefour · Leclerc · ADEME · WWF |

---

## ⚙️ Tech stack

| Layer | Technology |
|---|---|
| Mobile | React Native 0.83 · Expo SDK 55 · TypeScript |
| Auth | Firebase Auth · Google Sign-In · Email verification |
| Database | Firestore — real-time onSnapshot, production security rules |
| Local cache | AsyncStorage — Local First, always written first |
| Barcode | Open Food Facts API — EAN global index, label enrichment |
| CO₂ | Agribalyse hybrid engine + per-category fallback |
| Analytics | Custom pipeline → Firestore → BigQuery (europe-west3) |
| Monitoring | Sentry — ErrorBoundary, DSN production, email alerts |
| Build | EAS Build · com.gaspicheck.app · versionCode 2 |

---

## 🗺️ Roadmap

| Version | Status | Highlights |
|---|---|---|
| V1.0 → V6.5 | ✅ Done | Core gamification, barcode scanner, CO₂ engine, notifications |
| V7.0 → V8.0 | ✅ Done | Firebase Auth · Local First Cloud Sync · multi-device |
| V8.5 | ✅ Done | Barcode Analytics V2 · Family Fridge 6 members real-time |
| V9.5 | ✅ Done | Google Sign-In · GDPR Kill-Switch · Community Impact screen |
| V9.5.5 | ✅ Done | BigQuery pipeline · 37 analytics fields · Sentry · 5 Cloud Functions |
| **V10.0** | 🔜 **Coming** | **Google Play Store · Looker Studio dashboard · iOS TestFlight** |

---

## 👤 Author

**Gaspicheck-Labs** — Solo builder · 280+ commits · 0 burnout.

*Built with React Native, Firebase, and an unreasonable amount of conviction.*

**🌐 [gaspicheck.com](https://gaspicheck.com) · 📧 [contact@gaspicheck.com](mailto:contact@gaspicheck.com)**
