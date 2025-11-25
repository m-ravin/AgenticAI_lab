# AgenticAI_lab

AgenticAI_lab is a collection of notebooks and small demos that explore building agentic behavior and LangGraph-style workflows using Python. The repository contains example notebooks, and project metadata in `pyproject.toml`.

**Quick summary**
- **Language:** Python 3.12+
- **Contents:** interactive Jupyter notebooks demonstrating LangGraph basics and chatbot patterns

## Repository Structure

- `main.py` : small runnable entry point / demo script (if present).
- `pyproject.toml` : project metadata and dependencies.
- `1-LangGraph Basics/` : folder with notebooks:
	- `1.1-simplegraph.ipynb` — simple graph examples
	- `1.2-chatbot.ipynb` — chatbot demo using tools
	- `1.3-DataclassStateSchema.ipynb` — state schema with dataclasses
	- `1.4-ChatborWithMultipleTools.ipynb` — multi-tool chatbot examples

## Prerequisites

- Python 3.10 or newer
- `pip` (for installing `uv` if not already installed)
- `uv` — the project uses `uv` for environment and dependency management (examples below)
- Jupyter or JupyterLab for opening the notebooks

## Quick Setup (using `uv`)

This repository uses `uv` to manage dependencies and shells. Replace the example commands below with the exact `uv` subcommands you use if they differ.

1. Install `uv` if you don't already have it (example via `pip`):

```bash
pip install uv
```

2. Install or sync dependencies (if your `uv` workflow separates add vs install):

```bash
uv sync
```


