# 🚀 QuickStart

[![CI](https://github.com/Ruh-Al-Tarikh/quickstart/actions/workflows/ci.yml/badge.svg)](https://github.com/Ruh-Al-Tarikh/quickstart/actions/workflows/ci.yml)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

A minimal, developer-friendly **Python starter template** for building **Prefect workflows**, **CLI tools**, or **reusable libraries** — fast.

Perfect for automation, orchestration, experiments, and learning without boilerplate overload.

---

## ✨ What This Template Is For

This repo is designed to be flexible. You can use it as:

- 🧭 **Prefect automation project** (flows, tasks, deployments)
- 🖥️ **CLI tool** (`quickstart run`, `quickstart deploy`, etc.)
- 📦 **Python library** (importable, testable, publishable)

---

## 📚 Table of Contents

- [About](#about)
- [Project Layout](#project-layout)
- [Prerequisites](#prerequisites)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [Prefect Workflows](#prefect-workflows)
- [CLI Usage](#cli-usage)
- [Development](#development)
- [Testing](#testing)
- [Linting & Formatting](#linting--formatting)
- [Packaging & Publishing](#packaging--publishing)
- [Continuous Integration](#continuous-integration)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## About

**QuickStart** is a clean Python starter project that includes:

- Virtual environments
- Editable installs
- Prefect-ready structure
- CLI entry points
- Testing, linting, formatting
- Packaging & CI support

Use it to bootstrap:
- Prefect automation pipelines
- Internal developer tools
- Lightweight Python services
- Learning or prototyping projects

---

## Project Layout

```text
quickstart/
├─ quickstart/
│  ├─ __init__.py
│  ├─ flows.py        # Prefect flows
│  ├─ tasks.py        # Prefect tasks
│  ├─ cli.py          # CLI entry point
│  └─ core.py         # Shared library logic
├─ tests/
├─ pyproject.toml
├─ requirements.txt
├─ requirements-dev.txt
└─ README.md
