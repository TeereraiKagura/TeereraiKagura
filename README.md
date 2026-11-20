# Hi, I'm Teererai Kagura

**Chemical engineer turned software developer · Computer Science student at NUST · Zimbabwe**

I came to software from chemical engineering, and I build the same way an engineer designs a plant:
model the system first, enforce the rules where they can't be bypassed, and measure before claiming anything works.
Most of my projects start from a real problem around me, such as student-housing scams, prepaid airtime, small-business
bookkeeping and job hunting.

---

## Featured projects

### 📊 Data and databases

**[prepaid-telco-db](https://github.com/TeereraiKagura/prepaid-telco-db)** · PostgreSQL 16, Flyway, Docker, GitHub Actions
A database for a prepaid mobile network: airtime ledger, top-ups, vouchers, bundles and usage charging.
Balances are enforced by triggers, usage tables are partitioned by month, and the repo includes 15 business-question SQL queries.
55+ SQL tests run in CI against a real Postgres on every push.

**[QuantSport](https://github.com/TeereraiKagura/quantsport)** · Python, pandas, scikit-learn, XGBoost, statsmodels, FastAPI, Streamlit
A football prediction research platform across 8 leagues, built in eight phases: data ingestion, Dixon–Coles and ML models,
odds comparison, walk-forward backtesting, risk management, a dashboard and automation.
It makes no profit claims unless a result is reproducible and comes with a sample size and confidence interval.

### 🤖 Automation

**[Jobsearch-Agent](https://github.com/TeereraiKagura/Jobsearch-Agent)** · TypeScript, Playwright, Vitest, Claude API (optional)
A scheduled agent that searches LinkedIn, removes duplicate listings, scores each role against a candidate brief
with a rubric you can audit, and writes ranked reports. Scoring is free and rule-based by default, every link comes
from a page the agent actually loaded, and coverage limits are reported rather than hidden.

### 🌐 Full-stack web

**[NUST Student Portal](https://github.com/TeereraiKagura/nust-student-portal)** · Node.js, Express 5, SQLite, vanilla JS · [Live demo](https://nust-student-portal.onrender.com)
A full-stack coursework recreation of the university portal, with student and staff roles, course registration,
marks upload, bursary balances and simulated payments. Passwords are bcrypt-hashed, sessions run on the server,
and API tests use `node:test` and supertest.

### 🧾 Tools for small businesses

| Project | What it does | Demo |
|---|---|---|
| [Club Cubana](https://github.com/TeereraiKagura/clubcubana-) | Nightclub management that replaces the notebook: live net profit (COGS from stock counts), stock alerts and expense tracking | [Live](https://clubcubana.vercel.app) |
| [Haven & Home Invoice Suite](https://github.com/TeereraiKagura/Haven-and-Home-Invoice-and-Quotation-Suite) | Offline-first quotes and invoices that survive power cuts, with USD/ZiG/ZAR and 15.5% VAT, and print-ready A4 | — |
| [Oryx Masvingo](https://github.com/TeereraiKagura/oryx-masvingo-app) | Mobile booking page for delivery, freight and car rental. Orders are validated and sent to the business as WhatsApp messages, with no backend needed | — |
| [Student Record System](https://github.com/TeereraiKagura/student-record-system-Merge-Sort) | Data-structures project applying merge sort to student records, with CRUD and live search | [Live](https://student-record-system-merge-sort.vercel.app) |

---

## Tech I use

**Languages:** TypeScript · JavaScript · Python · SQL (PL/pgSQL) · HTML/CSS
**Backend and data:** Node.js · Express · Prisma · PostgreSQL · SQLite · Supabase · pandas · scikit-learn · FastAPI
**Frontend:** React · Vite · Tailwind CSS · Streamlit
**Tooling:** Git · GitHub Actions · Docker · Flyway · Playwright · Vitest · Vercel · Render

---

## What I'm looking for

Junior software, data or automation roles, and internships, especially where an engineering background helps:
process and industrial data, operations tooling, or anything that has to stay correct under real-world constraints.
