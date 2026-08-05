# Hi, I'm Matteo

AI Engineer building production AI agent systems and ML pipelines.

### Tech Stack

`Python` `LangGraph` `Kedro` `FastAPI` `Langfuse` `Ragas` `MCP` `PyTorch` `Docker` `Railway` `Streamlit`

### Main Projects

**Macro Report Pipeline** — Scheduled workflow that generates a daily macro report: pulls FRED/ECB data, computes metrics and anomalies, one LLM writes the commentary and a second reviews it against the numbers, with human approval before shipping to Slack. *(Generator-Critic · HITL)*

**Central Bank Watcher** — Multi-agent system tracking monetary-policy stance across 5 central banks; parallel scanners classify each bank's stance, a supervisor flags divergences, an LLM-as-judge scores answers on Langfuse. *(Multi-Agent · Map-Reduce · Generator-Critic)*

**Financial Research Agent** — Multi-agent researcher where a supervisor routes each query to only the specialists it needs across 7 agents (news, fundamentals, SEC filings, macro), then a writer and a reviewer loop. *(Multi-Agent · Supervisor)*

**Document Q&A Agent** — RAG agent answering questions over user-uploaded documents with page-level citations; the LLM decides when to retrieve and re-searches when one pass isn't enough; answers scored with Ragas. *(Agentic RAG)*

**Portfolio Analyst Agent** — ReAct agent answering fund and portfolio questions in plain English (performance, risk, benchmarking, attribution, compliance) over a reproducible data pipeline.

**Economy & Markets Agents** — Two agents that interoperate via Google's Agent2Agent (A2A) protocol: Economy screens macro indicators across 25+ economies, Markets tracks returns, volatility and momentum across the major asset classes.

**Portfolio Dashboard** — 7-tab Streamlit app tracking 50+ risk, performance and benchmark metrics across the investment portfolios; Dockerised and cloud-deployed.

**Economic Dashboard** — 9-page Streamlit app consolidating 100+ macro and market indicators, used daily by the investment team; Dockerised and cloud-deployed.

**ML Recession Prediction** — ML pipeline predicting US recessions from macro time-series; detects 86% of recessions, validated on 65+ years of data.

**Portfolio Optimizer** — Michaud resampled efficiency with Monte Carlo simulation and constrained mean-variance optimisation across 4 risk levels; used for portfolio construction.
