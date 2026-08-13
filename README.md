<h1 align="center">Hi, I'm Mustafa 👋</h1>

<p align="center">
  <b>Student who ships.</b><br>
  I build products end-to-end — ML models, web apps, Telegram bots, iOS — and I'm starting to write about how.
</p>

<p align="center">
  <a href="mailto:kassymoff01@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Kazakhstan-00AFCA?style=flat-square&logo=googlemaps&logoColor=white" alt="Kazakhstan">
</p>

---

## About

- 🎓 Still a student — and shipping real products alongside coursework
- 🤖 Into **AI/ML and data**: ranking models, explainability, LLM-powered products
- 🚀 Into **shipping**: idea → live product → first real users, as fast as it takes
- 🛠 Into **building with AI agents** — most of my work now runs through Claude Code and custom skills
- ✍️ Writing about the **student-founder path**: hackathons, clients, mistakes, and juggling it with a degree

---

## Featured projects

### 🌾 [Dala.ai](https://github.com/user1618phi/dala-ai) — merit-based AI scoring for farm subsidies

> 🏆 Built for **Decentrathon 5.0** (Gov Case 2) — hackathon project, documented as a full case study

Kazakhstan distributes **139.3 bn ₸** of farm subsidies across **36,651 applications** a year, prioritized by a single criterion: *who clicked submit first*. A farm with 500 head of pedigree cattle can lose to a shell cooperative that applied five minutes earlier. Dala.ai replaces the queue with a merit-based score.

- LightGBM ranking model with **SHAP explanations** and a fairness audit across regions
- FastAPI backend · Next.js app with farmer/official roles · Streamlit analytics dashboard
- Model card, BPMN as-is/to-be and full methodology in the repo — data anonymized, no names or national IDs

**→ [Live analytics dashboard](https://frontend-production-3c07.up.railway.app)**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-FF6F00?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)

---

### 📿 [Asma: 99 Names](https://github.com/user1618phi/asma-99-ios-app) — iOS app for learning the 99 Names of Allah

Free, offline-first, no account. Russian, English and Kazakh — interface and content.

Most memorization apps let you mark a card "known" by looking at it. This one doesn't: flashcards only prepare a name, and it counts as learned once you retrieve it correctly under test. The engine is built on the **testing effect** (Roediger & Karpicke, 2006), the **spacing effect** (Cepeda et al., 2006) and **Fogg's behavior model** — every threshold in the code traces back to one of them.

- On-device speech recognition for pronunciation practice
- Gamification that never punishes: soft currency and cooldowns instead of streak guilt
- Optional CloudKit sync across devices, with no login
- [Learning engine fully documented](https://github.com/user1618phi/asma-99-ios-app/blob/main/docs/learning-engine.md) — state machine, HP economy, cooldowns

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0071E3?style=flat-square&logo=swift&logoColor=white)
![SwiftData](https://img.shields.io/badge/SwiftData-0071E3?style=flat-square)
![CloudKit](https://img.shields.io/badge/CloudKit-1BADF8?style=flat-square&logo=icloud&logoColor=white)

---

### 🛁 [Vita Lux](https://github.com/user1618phi/vita-lux) — e-commerce for a manufacturer

Online store for a Kazakh sanitary-ware manufacturer. Runs on a mock catalog when no database is present, which keeps CI green and onboarding to a single command.

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript_strict-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

### 🌱 [Sarqyt](https://github.com/user1618phi/sarqyt_web) — rescuing surplus food

Marketplace connecting restaurants with people willing to buy good food that would otherwise be thrown out. Kazakh/Russian localization, mobile-first.

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

---

## Client work

Code stays private — these are products built for companies. Here's what they do.

<table>
<tr>
<td width="50%" valign="top">

### 📦 Smart Procurement / P23
**RFQ → suppliers → delivery, end to end**

Upload an RFQ as Excel or CSV; the system finds suppliers, scores them, extracts contacts, then carries the order through quoting, invoicing, customs breakdown and delivery tracking.

- Supplier discovery with **deterministic rule-based scoring** — no LLM in the ranking path, so results stay reproducible and auditable
- Multi-tenant isolation · SSE live progress
- ~850 commits across frontend, API and search engine

`Next.js` `TypeScript` `FastAPI` `PostgreSQL`

</td>
<td width="50%" valign="top">

### 🏋️ OI BOI
**Fitness platform living inside Telegram**

Two Mini App funnels sharing one backend, plus an iOS companion app and an admin panel.

- **Visual bot builder**: paste a token from @BotFather, draw the scenario on a React Flow canvas, and users walk through it automatically
- ~530 commits across backend, two Mini Apps, studio, admin and iOS

`Next.js` `Prisma` `Supabase` `Telegram Bot API` `Swift`

</td>
</tr>
</table>

---

## Stack

**Web**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & data**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**ML**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Mobile & bots**
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)

---

## Now

- 🛠 Building **Vita Lux** and the **OI BOI** platform
- 📚 Studying — and treating every client project as the real curriculum
- ✍️ Setting up a blog about shipping products as a student

---

<p align="center">
  <i>Open to collaborations and interesting problems.</i><br>
  <a href="mailto:kassymoff01@gmail.com">kassymoff01@gmail.com</a>
</p>

<!-- Add once ready:
  LinkedIn: https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white
  X:        https://img.shields.io/badge/X-000000?style=flat-square&logo=x&logoColor=white
  Blog:     https://user1618phi.me
-->
