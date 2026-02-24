# Ignivox

<p align="center">
  <img src="./assets/branding/logo.svg" alt="Ignivox logo" width="88" />
</p>

![Language](https://img.shields.io/badge/language-Python%203.11%2B-blue)
![License](https://img.shields.io/github/license/smouj/Ignivox)
![Last Commit](https://img.shields.io/github/last-commit/smouj/Ignivox)
![CI](https://img.shields.io/github/actions/workflow/status/smouj/Ignivox/ci.yml?branch=main)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20this%20project-ff5f5f?logo=ko-fi&logoColor=white)](https://ko-fi.com/smouj013_dev)

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

**Legacy code modernization forge with safety-first refactoring.**

## Vision
Analyzes legacy code paths and proposes incremental, test-oriented transformations.

## What problem it solves
Legacy systems are fragile and risky to modernize manually.

## Core superpower
- ⚡ **Refactor orchestration with behavior-preserving verification workflow**

## Key use cases
- ✅ Migration planning
- ✅ Refactor assistance
- ✅ Code quality uplift
- ✅ Legacy risk reduction


## API surface
`POST /transform`, `GET /health`

## Technical stack
- **Core stack:** FastAPI + AST tooling + automated validation
- **Runtime:** local-first, self-hosted friendly
- **Infra:** Docker Compose + Caddy + Redis/Chroma/Ollama compatibility

## Current status (Feb 2026)
- ✅ Public scaffold available
- ✅ Bilingual README (EN default + ES)
- ✅ CI + release baseline configured
- 🚧 Feature hardening in progress

## Quick start
```bash
git clone https://github.com/smouj/Ignivox.git
cd Ignivox
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m src.ignivox.cli --help
```

## Documentation
- [Implementation Guide](./docs/IMPLEMENTATION.md)
- [Architecture](./docs/ARCHITECTURE.md)
- [Runbook](./docs/RUNBOOK.md)
- [Deployment Guide](./docs/DEPLOYMENT.md)
- [Release Process](./docs/RELEASE.md)
- [Changelog](./CHANGELOG.md)

## Contributing
Contributions are welcome. Please read [CONTRIBUTING.md](./CONTRIBUTING.md).

## License
MIT © 2026 smouj

---

### Other skills
Explore the full ecosystem here: **[smouj/smouj](https://github.com/smouj/smouj)**

**Signature:** [@Smouj013](https://x.com/smouj013)
