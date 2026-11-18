# Hi, I'm Nikko Echevarria 👋

**AI-directed product builder.** I turn business problems into working software by directing AI coding tools. Every project here was built with Claude Code: I defined the requirements and the safety rules, reviewed what the AI produced, tested it like a customer would, and pushed fixes until it worked.

I came up through Tier 1 technical support (SME and escalation point, 50+ users a day, HIPAA environment) and security training, so I focus on the end user and the failure cases. I'm not a hand-coder. My strength is knowing what a system needs to do, catching when the AI gets it wrong, and getting it shipped.

📍 Wesley Chapel, FL · 💼 [LinkedIn](https://linkedin.com/in/nikkoechevarria) · 🌐 [reelkix.com](https://reelkix.com)

---

## Featured projects

| Project | What it does | AI / engineering highlights |
|---|---|---|
| [**AI Revenue Recovery Engine**](https://github.com/reelkixmedia/ai-revenue-recovery-engine) | Connects to Jobber, Square or a CSV, finds stale quotes and lapsed clients, and follows up automatically by text and email. | Claude drafts every message; drafts with invented prices, discounts or links are rejected for a template. Consent, opt-outs, quiet hours and frequency caps enforced in code. FastAPI, Twilio, Stripe, 260+ tests. |
| [**Creator Audit System**](https://github.com/reelkixmedia/creator-audit-system) | Paid YouTube channel audits, from Stripe checkout to emailed PDF with no manual step. | Claude writes the analysis as structured JSON; a number-check step validates every figure against the source data. Postgres, GitHub Actions scheduling, end-to-end tests on SQLite and Postgres. |
| [**COI Tracker**](https://github.com/reelkixmedia/coi-tracker-ai) | Reads Certificates of Insurance, tracks expirations, and sends renewal requests at 30/14/7/0 days. | Built-in PDF reader with confidence scores and human-in-the-loop review; Claude extraction for scans and photos is built and unit-tested but not yet run live. Measured accuracy (built-in reader): 251/252 fields on text PDFs, and every wrong field was flagged for review. |
| [**Pro-Sync MLB Analytics**](https://github.com/reelkixmedia/prosync-mlb-analytics) | Daily MLB prediction pipeline ranking home-run and total-bases outcomes. | Statcast feature engineering, a ridge logistic regression (implemented without an ML library), nightly self-grading and calibration tracking. Streamlit. No LLM in the app itself. |
| [**Previsit Scanner**](https://github.com/reelkixmedia/previsit-scanner) | Flags expired prescriptions and overdue labs before patient visits (synthetic data only). | Security-first design: TOTP MFA, role-based access, per-practice encryption, hash-chained tamper-evident audit log. 58 tests. |

## Tools & platforms used in these builds

**AI:** Claude API (Anthropic), structured outputs, prompt engineering, document extraction, guardrails & validation, human-in-the-loop review, accuracy evaluation, Claude Code
**Backend:** Python, FastAPI, REST APIs, webhooks, OAuth, PostgreSQL, SQLite, pytest, Streamlit
**Integrations:** Stripe, Twilio, SMTP/Resend, YouTube Data API, Google Places API, Jobber, Square, MLB Stats API
**Ops & security:** Render, Netlify, Neon, GitHub Actions, Docker, Linux/WSL, MFA, RBAC, encryption, audit logging, HIPAA

## How I build

- **Direct the AI, own the outcome.** I write the requirements, Claude Code writes the code, and I test every flow and send back exact fixes until it works.
- **Safe by default.** Everything that contacts real people runs in dry-run mode until it's switched on.
- **Don't trust the model blindly.** AI output gets checked against source data, rejected when it invents facts, and routed to a human when confidence is low.
- **Measure it.** Tests for the code, accuracy reports for the AI, and nightly grading for predictions.

📫 Open to AI Automation, AI Implementation and Solutions roles. Reach me on [LinkedIn](https://linkedin.com/in/nikkoechevarria).
