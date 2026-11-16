# Hi, I'm Nikko Echevarria 👋

**AI automation builder.** I design and ship Claude-powered business systems end to end — integrations, AI output with guardrails and validation, payments, messaging, scheduling, and automated tests.

I came up through Tier 1 technical support (SME and escalation point, 50+ users a day, HIPAA environment) and security training, so I build with the end user and the failure cases in mind. I use AI-assisted development (Claude Code) heavily, and every project here is tested and documented.

📍 Wesley Chapel, FL · 💼 [LinkedIn](https://linkedin.com/in/nikkoechevarria) · 🌐 [reelkix.com](https://reelkix.com)

---

## Featured projects

| Project | What it does | AI / engineering highlights |
|---|---|---|
| [**AI Revenue Recovery Engine**](https://github.com/reelkixmedia/ai-revenue-recovery-engine) | Connects to Jobber, Square or a CSV, finds stale quotes and lapsed clients, and follows up automatically by text and email. | Claude drafts every message; drafts with invented prices, discounts or links are rejected for a template. Consent, opt-outs, quiet hours and frequency caps enforced in code. FastAPI, Twilio, Stripe, 260+ tests. |
| [**Creator Audit System**](https://github.com/reelkixmedia/creator-audit-system) | Paid YouTube channel audits, from Stripe checkout to emailed PDF with no manual step. | Claude writes the analysis as structured JSON; a number-check step validates every figure against the source data. Postgres, GitHub Actions scheduling, end-to-end tests on SQLite and Postgres. |
| [**COI Tracker**](https://github.com/reelkixmedia/coi-tracker-ai) | Reads Certificates of Insurance (PDF or photo), tracks expirations, and sends renewal requests at 30/14/7/0 days. | AI document extraction with confidence scoring and human-in-the-loop review. Measured accuracy: 251/252 fields on text PDFs, and every wrong field was flagged for review. |
| [**Pro-Sync MLB Analytics**](https://github.com/reelkixmedia/prosync-mlb-analytics) | Daily MLB prediction pipeline ranking home-run and total-bases outcomes. | Statcast feature engineering, a ridge logistic regression written from scratch, nightly self-grading and calibration tracking. Streamlit. |
| [**Previsit Scanner**](https://github.com/reelkixmedia/previsit-scanner) | Flags expired prescriptions and overdue labs before patient visits (synthetic data only). | Security-first design: TOTP MFA, role-based access, per-practice encryption, hash-chained tamper-evident audit log. 58 tests. |

## Toolbox

**AI:** Claude API (Anthropic), structured outputs, prompt engineering, document extraction, guardrails & validation, human-in-the-loop review, accuracy evaluation, Claude Code
**Backend:** Python, FastAPI, REST APIs, webhooks, OAuth, PostgreSQL, SQLite, pytest, Streamlit
**Integrations:** Stripe, Twilio, SMTP/Resend, YouTube Data API, Google Places API, Jobber, Square, MLB Stats API
**Ops & security:** Render, Netlify, Neon, GitHub Actions, Docker, Linux/WSL, MFA, RBAC, encryption, audit logging, HIPAA

## How I build

- **Safe by default.** Everything that contacts real people runs in dry-run mode until it's switched on.
- **Don't trust the model blindly.** AI output gets checked against source data, rejected when it invents facts, and routed to a human when confidence is low.
- **Measure it.** Tests for the code, accuracy reports for the AI, and nightly grading for predictions.

📫 Open to AI Automation, AI Implementation and Solutions roles. Reach me on [LinkedIn](https://linkedin.com/in/nikkoechevarria).
