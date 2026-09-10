<h1 align="center">Hi, I'm Mustafa 👋</h1>

<p align="center">
  <b>Student who ships.</b><br>
  I build products end-to-end: LLM systems, ML models, web apps, Telegram bots, native iOS and Android.
</p>

<p align="center">
  <a href="mailto:kassymoff01@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Astana,_Kazakhstan-00AFCA?style=flat-square&logo=googlemaps&logoColor=white" alt="Kazakhstan">
</p>

---

## About

- 🎓 Student at QAIRU, Astana. CTO of **QairuHub**, the student builders' organization: four product tracks, fifteen people, most of them on their first project
- 🤖 **LLM and ML products**: retrieval with guarantees about what the model may not invent, explainable scoring, cost-aware AI in production
- 🚀 **Shipping**: idea → live product → first paying users. Solo, end to end, including the App Store
- 🛠 **Building with AI agents**: Claude Code and Codex are my daily tools, and every repo carries the rules they work by
- 🏆 1st place, nFactorial LLM Hackathon 2024 · nFactorial Incubator 2024 (full scholarship)

---

## Featured projects

### 🧠 [The Persona Factory](https://github.com/user1618phi/persona-factory) — an LLM editor that refuses to invent

A private Telegram editor that writes in one person's voice from **confirmed rules, real voice samples and verified experiences**, and nothing else. Books are knowledge, never identity. Chat exports are language samples, never biography. New facts enter only through a human `/review`.

- LiteLLM fallback chain (Gemini → Groq → Cohere → OpenRouter), Groq Whisper for voice notes
- Supabase pgvector retrieval reranked by recency: `similarity × exp(−λ · age)`
- Semantic chunking of books and chat exports, separate slim production image and heavy ingest image
- 116 tests with every network call mocked, SQL migrations validated with pglast

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase_pgvector-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-1C3C3C?style=flat-square)
![Telegram](https://img.shields.io/badge/aiogram-26A5E4?style=flat-square&logo=telegram&logoColor=white)

---

### 🚿 [TazaCRM](https://github.com/user1618phi/tazacrm) — management accounting for car washes

The competitor is a paper notebook: 8 seconds per entry, in a concrete box with no stable Wi-Fi. TazaCRM does intake in **15 seconds**, payroll by percentage, month close, cash reconciliation and a morning Telegram summary. Web app plus native **iOS and Android** clients on one OpenAPI 3.1 contract. In production; iOS in App Store review. Code is private, the case study is public.

- Real row-level security per tenant (32 policies in the Drizzle schema), audit log by Postgres triggers
- Offline-first: one write path through an IndexedDB queue, five cars in airplane mode is an acceptance test
- AI intake as a cascade: on-device speech → deterministic parser with tests → Claude only as fallback, per-tenant daily budget
- 22 numbered architecture decisions; code that contradicts one is not written

![Next.js](https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square)
![Swift](https://img.shields.io/badge/SwiftUI-F05138?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Compose-7F52FF?style=flat-square&logo=kotlin&logoColor=white)

---

### 🌾 [Dala.ai](https://github.com/user1618phi/dala-ai) — merit-based AI scoring for farm subsidies

> 🏆 Decentrathon 5.0, Gov Case 2. 135 commits in nine days, documented as a full case study.

Kazakhstan distributes **139.3 bn ₸** of farm subsidies across **36,651 applications** a year, prioritized by who clicked submit first. Dala.ai replaces the queue with an explainable merit score.

- LightGBM tuned with Optuna, **SHAP** explanations for every score, a fairness audit across regions
- **RAG over the subsidy regulation** (ChromaDB + lexical) with separate prompts for farmers and officials
- Antifraud flags override the model; per-oblast pasture norms extracted from the government PDF
- FastAPI · Next.js app with farmer/official roles · Streamlit dashboard · model card · CI

**→ [Live analytics dashboard](https://frontend-production-3c07.up.railway.app)**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-FF6F00?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB_RAG-FF6B35?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

---

### 📿 [Asma: 99 Names](https://github.com/user1618phi/asma-99-ios-app) — iOS app for learning the 99 Names of Allah

Free, offline-first, no account. Russian, English and Kazakh, interface and content. Shipped to the App Store in May 2026.

Flashcards only prepare a name; it counts as learned once you retrieve it correctly under test. The engine is built on the testing effect, the spacing effect and Fogg's behavior model, and [every threshold is documented](https://github.com/user1618phi/asma-99-ios-app/blob/main/docs/learning-engine.md).

- On-device speech recognition for pronunciation practice
- Gamification that never punishes: soft currency and cooldowns instead of streak guilt
- Optional CloudKit sync with no login

![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0071E3?style=flat-square&logo=swift&logoColor=white)
![SwiftData](https://img.shields.io/badge/SwiftData-0071E3?style=flat-square)
![CloudKit](https://img.shields.io/badge/CloudKit-1BADF8?style=flat-square&logo=icloud&logoColor=white)

---

## Also public

- 🛁 [**Vita Lux**](https://github.com/user1618phi/vita-lux) — e-commerce for a sanitary-ware manufacturer. pnpm monorepo, Drizzle, ru/kk localization with a linter for the nine Kazakh-only glyphs (ә ө ұ ү қ ң ғ һ і), so a translation can never silently degrade into Russian. CI on every push.
- 🌱 [**Sarqyt**](https://github.com/user1618phi/sarqyt_web) — marketplace that rescues surplus food from restaurants. Next.js, kk/ru.

## Client work (code stays private)

<table>
<tr>
<td width="50%" valign="top">

### 📦 Smart Procurement
**RFQ → suppliers → delivery, end to end**

Upload an RFQ as Excel or CSV; the system finds suppliers, classifies items with Claude Haiku behind a two-level cache, extracts and validates contacts, then carries the order through quoting, invoicing, customs and cargo tracking.

- Deterministic rule-based supplier scoring, so results stay reproducible and auditable
- Tiered scraping cascade: plain HTTP first, headless browser only for JS-rendered sites
- ~850 commits across frontend, API and search engine over 18 months

`FastAPI` `PostgreSQL` `Next.js` `Playwright` `Anthropic`

</td>
<td width="50%" valign="top">

### 🏋️ OI BOI
**Fitness platform living inside Telegram**

Two Mini App funnels sharing one backend, plus a native iOS app and an admin panel. Three paid products with real subscriptions and entitlements.

- **Visual bot builder**: paste a token from @BotFather, draw the scenario on a React Flow canvas, users walk through it automatically
- ~530 commits across backend, two Mini Apps, studio, admin and iOS

`Next.js` `Prisma` `Supabase` `Telegram Bot API` `Swift` `StoreKit`

</td>
</tr>
</table>

---

## Stack

**LLM & retrieval**
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=google&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-1C3C3C?style=flat-square)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B35?style=flat-square)
![Whisper](https://img.shields.io/badge/Whisper-412991?style=flat-square&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**ML & data**
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-02569B?style=flat-square)
![SHAP](https://img.shields.io/badge/SHAP-FF6F00?style=flat-square)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)

**Web**
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Mobile & bots**
![Swift](https://img.shields.io/badge/SwiftUI-F05138?style=flat-square&logo=swift&logoColor=white)
![Kotlin](https://img.shields.io/badge/Jetpack_Compose-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)

**Infra & tooling**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-191919?style=flat-square&logo=anthropic&logoColor=white)

---

## Now

- 🚿 Getting **TazaCRM** through App Store review and onto its first car washes
- 🏛 Building **QairuHub**: the community platform, the internal core platform and a schedule bot for QAIRU students
- 🧠 Next thing to learn properly: fine-tuning open models for Kazakh, speech in particular

---

<p align="center">
  <i>Open to collaborations and interesting problems.</i><br>
  <a href="mailto:kassymoff01@gmail.com">kassymoff01@gmail.com</a>
</p>
