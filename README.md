# Hi, I'm Lalith 👋

**I build complete products with AI — from an open question to something people use — and I bring 4+ years of data work to knowing whether they're working.**

I take an idea through scoping, interface, backend, data and AI, and I stay accountable for what ships: tests, customer-data handling, and measuring what happens after launch. I use AI (Claude, GPT) heavily to explore, prototype, implement and debug, and I verify its output with tests and evals rather than trusting it.

- 🛠️ **Building:** full-stack products in Python (FastAPI) with LLM features — structured outputs, fallbacks, evals, human-in-the-loop
- 📊 **Background:** Data Scientist at **USF Morsani College of Medicine** (395,000+ records, 180+ automated statistical comparisons) and data analyst at **Tata Consultancy Services** (multi-million-row banking data)
- 🎓 **M.S. in AI & Business Analytics**, University of South Florida (GPA 3.88)
- 🎯 **Open to:** product engineer, AI engineer and full-stack roles
- 📫 [LinkedIn](https://www.linkedin.com/in/klalithsagar/) · [Email](mailto:lalithsagar.kondapalli.ai@gmail.com)

## 📌 Products I've built end to end

| Project | The problem | What I owned |
|---|---|---|
| [**Pulse**](https://github.com/lalithsagarkondapalli/pulse) | Brands collect NPS but don't know what to fix, and unhappy customers never hear back | Whole product: mobile survey with instant rewards, Claude-tagged themes with PII redaction and fallback, dashboard ranking themes by detractors, consent-gated close-the-loop queue. FastAPI, SQLite, 22 tests incl. concurrency, CI, [decision log](https://github.com/lalithsagarkondapalli/pulse/blob/main/DECISIONS.md) |
| [**Computer-Use Automation System**](https://github.com/lalithsagarkondapalli/computer-use-automation-system) | LLM browser agents are slow, costly and unpredictable on every run | An LLM discovers a workflow once; it's compiled into a typed artifact that replays deterministically with zero LLM calls, with policy checks and same-session human handoff. 229 tests, real model evidence including failures |
| [**LLM Judge Eval**](https://github.com/lalithsagarkondapalli/llm-judge-eval) | Can you trust an LLM to grade answers? | Rubric judge with strict JSON output, blind human-labelling tool, and the stats to validate it (weighted κ, known-error controls, length-bias tests) |
| [**Clinical EDC Import Validator**](https://github.com/lalithsagarkondapalli/clinical-edc-import-validator) | Partner data arrives in four formats and nothing may be lost or silently changed | Spec-driven integration pipeline: every record loaded or rejected with a reason, 3-way reconciliation, hash-chained audit trail, 50 tests traced to requirements |

## 📈 Data & experimentation (how I decide what's working)

| Project | What it answers |
|---|---|
| [**E-mail Campaign Experiment**](https://github.com/lalithsagarkondapalli/email-campaign-experiment) | Which campaign e-mail should a retailer send, and to whom? 64,000-customer randomized test: SRM and balance checks, Holm-corrected effects, uplift targeting — and the call *not* to build targeting |
| [**Marketplace Data Warehouse**](https://github.com/lalithsagarkondapalli/marketplace-dw) | Monthly ELT for an e-commerce marketplace: Airflow, dbt star schema, SCD Type 2, 50 data tests |
| [**iBuyer Offer Engine**](https://github.com/lalithsagarkondapalli/ibuyer-offer-engine) | How to price home offers under uncertainty: conformal intervals and an adverse-selection backtest on 20,220 resales |

## 🤖 How I build with AI

1. **Scope first.** Write down the customer problem and what's out of scope before generating any code.
2. **Let AI draft, then verify by behaviour.** Tests on the real user path, screenshots of the real UI, evals on labelled data — not just reading the diff.
3. **Never put the model on the critical path without a fallback.** Validate outputs against a schema, redact customer data before it leaves the server, degrade gracefully.
4. **Keep the evidence honest.** Failures, limitations and "not launched yet" are written down, not hidden.

## 🛠️ Stack

**Product:** Python · FastAPI · SQL (PostgreSQL, SQLite, DuckDB) · HTML/CSS/Jinja · REST APIs · Playwright · Docker · GitHub Actions · pytest  
**AI:** Anthropic & OpenAI APIs · structured outputs · RAG (FAISS) · LLM evaluation · agents with human-in-the-loop  
**Data:** pandas · statsmodels · scikit-learn · LightGBM · Airflow · dbt · Spark/Databricks · Snowflake · MLflow · A/B testing & causal inference
