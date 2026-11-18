# Yusen Rong

**AI Engineer | AI Solutions Specialist | Data Scientist** · UBC Master of Data Science

I build LLM agents and RAG systems that show their work: every answer traces to a source, and every release is tested against a benchmark before it ships.

Open to AI Engineer, AI Solutions Specialist and Data Scientist roles. Authorized to work in Canada and relocating to Toronto.

## Featured work

### [newsletter-agent](https://github.com/yusenrong46-afk/newsletter-agent)

An open-source agent that reads Gmail through a local MCP server and writes a cited daily briefing, with a cost preview and a hard budget before any model call. A two-minute demo runs the real pipeline on about 170 synthetic emails.

`Python` `MCP` `OpenAI API` `pytest`

### [BC Zoning Verification Dashboard](https://github.com/yusenrong46-afk/burnaby-verification-dashboard) · UBC capstone with Green Metrics Technology

A client-sponsored team project in UBC's Master of Data Science program, where I owned rule verification. Across Burnaby, Calgary and Vancouver, 126 of 350 candidate rules were auto-verified at 1.00 precision with zero false verifications, and 130 went to a human review queue. This scoped result does not establish full-bylaw accuracy or completeness.

Continued after the capstone in [F1_intelligence_command](https://github.com/yusenrong46-afk/F1_intelligence_command). Portfolio Standard upgrade in review ([draft PR #1](https://github.com/yusenrong46-afk/F1_intelligence_command/pull/1), not merged): levels L2 to L5 pass on the branch; L1 is blocked on an upstream source change, because the official bylaw PDFs changed after the benchmark was built. Measured 2026-11-18 with `make eval`: the same 126 verified rules at precision 1.00 with 0 false verified.

`Python` `Streamlit` `RAG`

### [JournalPulse](https://github.com/yusenrong46-afk/JournalPulse)

A deployed journaling app where AI reflection is opt-in per entry with explicit consent. 1,270 backend tests at 91.88% coverage, 217 frontend unit tests and 22 integration tests against real PostgreSQL.

Portfolio Standard upgrade in review ([draft PR #13](https://github.com/yusenrong46-afk/JournalPulse/pull/13), not merged): all five levels (L1 to L5) pass on the branch. Measured 2026-11-18 with `make eval`: 1,436 backend tests passed at 92.07% branch-aware coverage.

[Live app](https://journalpulse.vercel.app) · [Engineering guide](https://github.com/yusenrong46-afk/JournalPulse/blob/main/docs/ENGINEERING.md)

`Next.js` `FastAPI` `Supabase` `TypeScript`

### Canadian Grocery Price Monitor (source private)

Forecasts the next one to three months of grocery inflation for 12 food categories from official Statistics Canada prices, and shows how accurate those forecasts have been. Portfolio Standard upgrade in review (not merged): all five levels (L1 to L5) pass in CI on the branch. In a backtest on data through 2026-09, the 1-month forecast missed by 1.46 percentage points on average across 1,104 out-of-sample forecasts, 12% lower than a no-change forecast. No public demo yet.

`Python` `statsmodels` `scikit-learn` `Streamlit`

### [Canada Investor Dashboard](https://github.com/yusenrong46-afk/Canada_Investor_Dashboard)

Property valuation for Vancouver and Halifax: XGBoost and Random Forest models on a DuckDB warehouse of 21,483 observations, with conformal intervals whose coverage is measured and SHAP drivers.

`Python` `XGBoost` `DuckDB` `SQL` `React`

### FireLens (source private)

A wildfire-information assistant for British Columbia where a LangGraph agent answers from official records through five read-only tools. Source stays private while source-reuse permissions are pending, and there is no public showcase yet; walkthrough on request. Portfolio Standard upgrade in review (not merged): all five levels (L1 to L5) pass in CI on the branch. Measured 2026-11-18 with `make eval`: 1,466 backend tests passed, and the answer guards refused 31 of 35 unsafe paraphrases, with 4 known gaps counted as failures.

`Python` `FastAPI` `LangGraph` `Redis` `React`

## How I work

Python, SQL, FastAPI, LangGraph, XGBoost, DuckDB and TypeScript. I build AI-assisted with Claude Code, Codex and Cursor, and I own the requirements, design decisions, tests and evaluation.

## Education

Master of Data Science, UBC Okanagan · B.S. in Computational Neuroscience with a minor in Applied Analytics, University of Southern California

## Contact

[LinkedIn](https://www.linkedin.com/in/yusen-rong-6b434a234/) · yusenrong46@gmail.com
