<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=8B5CF6&center=true&vCenter=true&width=700&lines=Hey%2C+I'm+Joseph.;I'm+building+an+AI+Dungeon+Master.;The+AI+suggests.+The+database+decides.;The+screen+just+shows+the+damage." alt="Typing intro" />

# ⚔️ JOSEPH — Character Sheet

**Class:** Full-Stack Developer · **Subclass:** AI-Native Systems · **Base:** Türkiye 🇹🇷

Solo developer — which mostly means I've personally made, and fixed, every mistake in this stack.

</div>

---

## 🎲 Ability Scores

*Self-assessed. No saving throw was rolled. Take with a grain of salt.*

| Stat | Score | Mod | In practice |
|------|:---:|:---:|-------------|
| 💪 **STR** — Stubbornness | 17 | +3 | Years into a solo FRPG engine and still not give up. That's dedication and consistency |
| ⚡ **DEX** — Frontend | 14 | +2 | React Native + Expo on mobile; React, Three.js and GSAP on web |
| 🛡️ **CON** — Backend Endurance | 15 | +2 | 505 Postgres functions and counting. Someone has to maintain them, and that someone is me |
| 🧠 **INT** — System Architecture | 16 | +3 | A +99-table PostgreSQL schema with RLS on every table — no exceptions, no "we'll fix it later" |
| 🔮 **WIS** — AI Engineering | 15 | +2 | LLM pipelines where the AI proposes and the server decides. Learned the hard way why that order matters |
| ✨ **CHA** — Product Sense | 20 | +5 | The table did say *self-assessed*. But baking the free/premium split into the architecture itself? That was a natural 20 |

---

## 📜 Main Quest: Fate of Mind

A mobile-first RPG where an AI acts as the Dungeon Master, following D&D 5e rules — built around one idea: **the AI is not allowed to touch reality.**

```mermaid
flowchart LR
    A["🔮 AI<br/><i>suggests</i>"] -->|"_change deltas only"| B["🗄️ Database<br/><i>decides & writes</i>"]
    B -->|"validated state"| C["📱 App<br/><i>displays</i>"]
    style A fill:#7c3aed,color:#fff
    style B fill:#1e293b,color:#fff
    style C fill:#0ea5e9,color:#fff
```

The AI never rolls dice and never edits a stat. It writes proposals (`_change` fields); only the server validates them and updates the real state (`_current`). Cheating isn't against the rules — it's structurally impossible. You can't fake a nat 20 when the dice live on the server.

| | |
|---|---|
| ⚙️ **Stack** | React Native 0.81 + Expo 54 · Supabase PostgreSQL + Edge Functions (Deno) · Mistral AI |
| 🗄️ **Numbers** | 112 tables · 505 functions · 272 RLS policies · server-side 4-phase dice |
| 💰 **Modes** |  Sandbox (lightweight) ·  FRPG (full D&D experience) — different cost profiles by design |
| 🎯 **Status** | Pre-launch. Taking my time on purpose — I'd rather ship late than ship with security holes |

---

## 🗡️ Side Quests

**🌌 Togu Nexus** — a community platform with events, forums and role-based moderation. React, TypeScript, Three.js, GSAP — I wanted it to feel like a place, not a webpage. Supabase Realtime keeps the event board live.

**🤬 Turkish Profanity Detection ML** — a pipeline for detecting Turkish profanity and slang, including the creatively misspelled kind. I built the labeled dataset myself; Turkish internet slang mutates fast, and off-the-shelf filters don't stand a chance.

**🎭 Ozan Engine** — a small interactive narrative engine living inside Togu Nexus. Typed, tested, and fun to break.

---

## 🎒 Inventory

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Deno](https://img.shields.io/badge/Deno-000000?style=for-the-badge&logo=deno&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

## 🧭 Alignment

- **Never trust the client** — in games or anywhere else. The player doesn't get to roll their own dice.
- **Documentation is for future me.** He shows up three months later with no memory and a lot of questions.
- **No deadline is a feature.** Use the freedom to get things right, not just done.

---

<div align="center">

## 📬 Send a Raven

[![Email](https://img.shields.io/badge/Email-yusufemredogan.2003%40gmail.com-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yusufemredogan.2003@gmail.com)

<!-- Replace USERNAME with your GitHub username and uncomment to activate stats cards:
<img src="https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=midnight-purple&hide_border=true" />
-->

</div>
