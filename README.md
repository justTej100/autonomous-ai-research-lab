# Autonomous Research Lab

An open-source self-hosted AI research laboratory that uses autonomous agents to conduct computer science research, run experiments, analyze results, and generate academic papers.

## Overview

Connect API keys from providers such as OpenAI, Anthropic, and DeepSeek to power specialized research agents.

The system coordinates agents through an autonomous research pipeline:

```text
Idea → Literature Review → Hypothesis
  → Methodology → Implementation → Experiments
  → Analysis → Peer Review → Manuscript
```

## Features

- **Multi-provider support:** Use your own LLM API keys.
- **Autonomous agents:** Specialized research, coding, analysis, and writing agents.
- **Research harness:** Manage execution, tools, memory, permissions, and verification.
- **Literature review:** Search papers and manage citations.
- **Experimentation:** Execute code in isolated environments.
- **Statistical analysis:** Evaluate and interpret experimental results.
- **Reproducibility:** Track configurations, datasets, code, and results.
- **Manuscript generation:** Produce academic drafts and LaTeX documents.

## Potential Tech Stack

| Component | Technology |
|---|---|
| Frontend | React, TypeScript, Vite |
| Backend | Python, FastAPI |
| Database | PostgreSQL, pgvector, Redis |
| AI Providers | OpenAI, Anthropic, DeepSeek |
| Agent Runtime | Custom harness, LangGraph |
| Execution | Docker |
| Research | NumPy, SciPy, pandas, scikit-learn, statsmodels |

## Potential Project Structure

```text
autonomous-research-lab/
├── frontend/
├── backend/
├── harness/
│   ├── runtime/
│   ├── providers/
│   ├── tools/
│   ├── memory/
│   ├── policy/
│   └── verification/
├── agents/
│   ├── literature/
│   ├── hypothesis/
│   ├── methodology/
│   ├── coding/
│   ├── experimentation/
│   ├── analysis/
│   ├── reviewer/
│   └── writing/
├── orchestrator/
├── research/
├── evaluation/
├── infrastructure/
└── tests/
```

## Getting Started

**Prerequisites:** Python 3.11+, Node.js 20+, Docker.

```bash
git clone YOUR_REPOSITORY_URL
cd autonomous-research-lab

python -m venv .venv
```

Activate the environment and install dependencies:

```bash
pip install -r backend/requirements.txt

cd frontend
npm install
```

Configure API credentials in `.env` using `.env.example` as a template.

## Roadmap

- [ ] Backend and frontend foundation
- [ ] LLM provider abstraction
- [ ] Core agent harness
- [ ] Tool execution and permissions
- [ ] Autonomous research workflows
- [ ] Literature retrieval and citation management
- [ ] Sandboxed experimentation
- [ ] Statistical analysis and evaluation
- [ ] Independent review agents
- [ ] LaTeX manuscript generation
- [ ] Reproducibility validation

## Research Principles

- Verifiable sources and citations
- Reproducible experiments
- Independent critical evaluation
- Transparent AI involvement
- Human accountability for research and publication


**Status:** Early development  
**Focus:** Autonomous research, multi-agent systems, and reproducible computer science.
