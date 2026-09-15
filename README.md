# Tarun Gudapati

### AI Developer and Deployment Engineer

I build AI features inside production software: LLM integrations, grounded retrieval, evaluation workflows, .NET services, and the delivery systems that make them dependable.

[Portfolio](https://tarun-gudapati.github.io/tarun-atelier/) · [LinkedIn](https://www.linkedin.com/in/tarun-gudapati/) · [Email](mailto:tarungudapati30@gmail.com)

Based in Hyderabad, India.

---

## Public AI Lab

### [Aegis Release Guard](https://github.com/Tarun-Gudapati/aegis-release-guard)
**Status: MVP** · .NET 10 · React · TypeScript · xUnit

Turns a unified git diff into an evidence-linked deployment risk review: transparent scoring, file-level findings, focused test suggestions, and a rollback checklist. It works locally with a deterministic analyzer and has an explicit opt-in boundary for an OpenAI-compatible provider.

### [TraceRAG](https://github.com/Tarun-Gudapati/trace-rag)
**Status: Concept scaffold with working local baseline** · .NET 10 · Retrieval · xUnit

Citation-first retrieval that chunks local documents, ranks evidence deterministically, returns verbatim extracts with citations, and refuses questions when support is insufficient. A claim-level self-check prevents unsupported generated text from being passed through.

### [IncidentSight](https://github.com/Tarun-Gudapati/incident-sight)
**Status: Concept scaffold with working deterministic baseline** · Python · FastAPI · Pydantic · Pytest

Extracts observable incident signals from logs, safely validates optional screenshot metadata, separates evidence from hypotheses, and keeps every proposed action human-approved. True image interpretation is deliberately left behind an unimplemented provider boundary.

### [ModelLedger](https://github.com/Tarun-Gudapati/model-ledger)
**Status: Concept scaffold with working offline baseline** · TypeScript · Node.js · Zod · Vitest

Runs deterministic regression gates over recorded LLM outputs and fails CI when configured quality, JSON validity, latency, or estimated-cost thresholds regress.

These repositories are deliberately explicit about maturity and limitations. They are original builds, not copied hackathon entries, and none claims an award or production deployment it has not earned.

---

## Production context

I work as a software engineer at **Safe Financials**, with previous experience at **AmpleLogic**. My work spans:

- AI and LLM integration inside existing products
- ASP.NET Core, C#, EF Core, and SQL Server
- Angular and TypeScript interfaces
- CI/CD, environment compatibility, release validation, and rollback design
- Product and visual design that survives implementation

Most employer work is private, so the public AI Lab exists to make my engineering decisions inspectable: contracts, tests, evidence, fallbacks, privacy boundaries, and honest trade-offs.

---

## How I approach AI software

```text
useful problem
  -> bounded model responsibility
  -> structured inputs and outputs
  -> evidence and evaluation
  -> explicit fallback
  -> monitored deployment
  -> human accountability
```

I do not treat the model call as the product. The surrounding system is what makes an AI feature reliable enough to use.

---

## Current stack

`C#` `.NET` `ASP.NET Core` `EF Core` `SQL Server` `Angular` `TypeScript` `React` `Python` `FastAPI` `LLM APIs` `RAG` `Evaluation` `Docker` `GitHub Actions`

---

## Contact

I am open to AI product engineering, .NET and Angular work, and teams that care about the last mile to production.

- Portfolio: [tarun-gudapati.github.io/tarun-atelier](https://tarun-gudapati.github.io/tarun-atelier/)
- LinkedIn: [linkedin.com/in/tarun-gudapati](https://www.linkedin.com/in/tarun-gudapati/)
- Email: [tarungudapati30@gmail.com](mailto:tarungudapati30@gmail.com)
