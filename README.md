<div align="center">

# Dobrin Rashkov

### Application Support Engineer → AI Systems & Automation

**Building reliable systems where humans, AI agents, and automation work together.**

`DOBRI AI LAB` · reliable automation · observable workflows · human-controlled AI

</div>

I work at the intersection of production support, software engineering, and AI-assisted development. I build systems that are reproducible, observable, reviewable, and safe to operate.

## Currently building

- **🤖 Dobri AI Orchestrator** — A multi-agent workflow controller under active development, designed around persistent state, provider abstraction, review boundaries, usage and capacity awareness, and human approval gates.
- **📈 Trading Bot Lab** — A paper-first automated research platform with reproducible evidence, isolated execution, deterministic validation, and fail-closed safety.
- **⚙️ Engineering Infrastructure** — Reliable automation, testing, deployment, observability, and AI-assisted engineering workflows.

## Featured engineering

### [Trading System Case Study](https://github.com/rashkov09/trading-system-case-study)

A paper-first research platform designed around deterministic testing, immutable and versioned evidence, isolated execution, reproducible deployment, stable APIs, and fail-closed safety.

The implementation remains private; the public case study documents the architecture and engineering decisions without exposing operational details or execution code.

### Dobri AI Orchestrator

**Case study coming soon.** A controlled multi-agent engineering system where implementers and reviewers operate through explicit workflow state, exact-version evidence, provider telemetry, CI, and human gates.

## System architecture

Reproducible evidence connects the research system end to end: inputs, revisions, evaluation decisions, runtime identity, and outcomes remain traceable.

```mermaid
flowchart TD
    A[Market Data] --> B[Collectors]
    B --> C[Immutable Evidence]
    C --> D[Research / Predictors]
    D --> E[Evaluation Gates]
    E --> F[Paper Trading Bot]
    F --> G[Stable API / Control Room]
```

## Dobri AI Lab workflow

Dobri AI Orchestrator is under active development. The intended workflow keeps implementation, review, automation, evidence, and final authority separate.

```mermaid
flowchart TD
    A[Human Owner] --> B[Orchestrator]
    B --> C[Gin<br/>Implement]
    B --> D[Jan<br/>Review]
    C --> E[CI / Automation]
    D --> E
    E --> F[Exact-Version Evidence]
    F --> G[Human Gate]
```

## Tech stack

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img alt="Java" src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111111">
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white">
  <img alt="SQL / SQLite" src="https://img.shields.io/badge/SQL%20%2F%20SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white">
  <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=111111">
  <img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
</p>

## How I engineer

- **Reproducible** — Deterministic results, exact versions, and immutable evidence.
- **Fail closed** — Missing or inconsistent evidence stays unknown rather than becoming false confidence.
- **Practical automation** — Use automation and AI to remove repetitive work without removing human ownership.
- **Continuous improvement** — Measure, review, learn, and iterate.

My application-support background shapes these principles: failures should be visible, important decisions traceable, deployments reversible, and consequential changes subject to clear technical and human boundaries.

## Earlier work

This account also contains earlier Java, database, university, and learning projects. They show where the journey started; the current systems work shows where it is heading.

---

> “I automate repetitive work because I'd rather spend the time solving the next problem.”
