# Nikita — Frontend Developer

Vue 3 · React · TypeScript · 6+ years building scalable, high-performance web apps. Based in Europe.

I like products that stay fast and readable as they grow: strict TypeScript, a real design system, tests that actually run in CI, and no CSS framework doing the thinking for me.

---

## 🌟 VibeOS — a personal life OS

**[Live demo](https://mrnednick.github.io/VibeOS)** · **[Source](https://github.com/MrNedNick/VibeOS)**

A single app for habits, tasks, goals, learning, training, notes and finance — where **everything is connected**. Check off a habit and its linked goal advances on its own. Log a workout and the habit checks itself off. One action cascades across modules, with nothing to wire up by hand.

![Vue](https://img.shields.io/badge/Vue_3-35495e?style=flat-square&logo=vue.js&logoColor=4FC08D) ![TypeScript](https://img.shields.io/badge/TypeScript-strict-3178c6?style=flat-square&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=flat-square&logo=vite&logoColor=white) ![Pinia](https://img.shields.io/badge/Pinia-ffd859?style=flat-square&logo=vue.js&logoColor=black) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

| | |
|---|---|
| **Scale** | 16 modules · 146 Vue components · ~52k lines of TS/Vue |
| **Tested** | 665 unit tests in 63 files (Vitest) + Playwright E2E, coverage gate in CI |
| **Fast** | 114 kB initial JS gzip, every module route lazy-loaded |
| **Accessible** | Lighthouse accessibility 100/100 |
| **Backend** | Supabase auth + row-level security, JSONB sync, offline queue, real-time merge |
| **Design system** | 22 in-house `@/ui` components, zero CSS frameworks, tokens-only styling |

**Engineering details I'm happy to talk about:**

- **Offline-first sync.** Versioned `localStorage` is the source of truth; a debounced push and an offline queue reconcile with Supabase. Soft-delete tombstones and `updatedAt` stamps make merges converge instead of resurrecting deleted rows.
- **Cross-module cascade.** A typed event bus lets a workout advance a habit, which advances a goal — without any module importing another. Regression-tested end to end.
- **Theming without JS.** Four "vibe-paks" (Dark, Light, Brutalist, CRT Retro) plus system-follow, implemented as pure CSS variable overrides on a `[data-theme]` attribute.
- **A CI guard against hardcoded hex colors,** because a design system only survives if something enforces it.

---

## Other work

| Project | What it is | Stack |
|---|---|---|
| **[oxfeeds-landing](https://github.com/MrNedNick/oxfeeds-landing)** | Marketing site for a search-traffic monetization partner — glassmorphism, scroll-reveal, 3D card tilt, count-up stats | Vue 3 · Vue Router · Vite |
| **[mobilynx-landing](https://github.com/MrNedNick/mobilynx-landing)** | Marketing site for a mobile performance-traffic network across 20+ GEOs | Vue 3 · Vue Router · Vite |

---

## Toolbox

![Vue](https://img.shields.io/badge/Vue.js-35495e?style=flat-square&logo=vuedotjs&logoColor=4FC08D)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![Nuxt](https://img.shields.io/badge/Nuxt-00DC82?style=flat-square&logo=nuxtdotjs&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Pinia](https://img.shields.io/badge/Pinia-ffd859?style=flat-square&logo=vuedotjs&logoColor=black)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## Get in touch

Open to frontend roles — Vue, React, TypeScript.

📫 **mrnednick@gmail.com**
