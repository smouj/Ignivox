# Ignivox

![Language](https://img.shields.io/badge/language-Python%203.11%2B-blue)
![Stars](https://img.shields.io/github/stars/smouj/Ignivox?style=social)
![Forks](https://img.shields.io/github/forks/smouj/Ignivox?style=social)
![License](https://img.shields.io/github/license/smouj/Ignivox)
![Last Commit](https://img.shields.io/github/last-commit/smouj/Ignivox)

**A code-forging flame that revives brittle software systems.**

## Vision
Ignivox is designed as a production-minded AI skill for the **smouj SuperAgents Universe**. It solves real operational friction by combining autonomous reasoning, local-first execution, and transparent decision traces. The goal is not just automation, but **reliable autonomy**: repeatable, auditable, and safe by default. It is built to operate standalone or as a module inside larger multi-agent systems.

## Core Superpower
- ⚡ **Legacy Code Revival and Refactor Forge**

## Current Status (February 2026)
- 🚧 In ideation and initial scaffolding phase
- Next milestones:
  - [ ] Define domain-driven folder structure
  - [ ] Ship minimal runnable CLI + config profile
  - [ ] Integrate Ollama local model gateway
  - [ ] Add one end-to-end functional example
  - [ ] Implement test suite (unit + smoke)
  - [ ] Publish full technical docs and architecture diagram

## Planned Architecture (2026 free/open-source stack)
- **Primary language:** Python 3.11+
- **Agent framework:** LangGraph
- **Local models:** Ollama (Llama 3.1, Qwen2.5, DeepSeek-Coder, Mistral)
- **Core dependencies:** tree-sitter, ruff, pytest, mypy, gitpython
- **Execution model:** local-first, optional self-hosted deployment (n8n / Railway / Fly.io free tier)

## Project Layout (planned)
```text
Ignivox/
├── src/
│   ├── core/           # domain logic and orchestration
│   ├── adapters/       # external connectors (API, DB, tools)
│   ├── memory/         # retrieval/state strategies
│   └── cli/            # operator commands
├── tests/
├── examples/
├── docs/
├── requirements.txt
└── README.md
```

## Installation (early scaffolding)
```bash
git clone https://github.com/smouj/Ignivox.git
cd Ignivox
pip install -r requirements.txt
```

## Roadmap Logic
1. **Foundation:** strict interfaces, typed contracts, config-first behavior
2. **Reasoning:** deterministic chains + fallback policy for critical actions
3. **Tooling:** adapter layer for browser, files, APIs, queues, and messaging
4. **Observability:** structured logs, metrics hooks, and replayable traces
5. **Safety:** policy gates for destructive or sensitive operations
6. **Scale-out:** compose with other skills through clean multi-agent boundaries

## Contribution
Contributions are welcome. Please read **CONTRIBUTING.md** before opening issues or PRs.

## License
MIT © 2026 smouj

Part of the **smouj SuperAgents Universe** → https://github.com/smouj/smouj
