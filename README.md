# Cross-Asset Correlation Analysis
**Stage:** Tooling Setup (Stage 02)

## Purpose
This project analyzes **time-varying cross-asset correlations** (equities, bonds, commodities) to guide diversification and risk management decisions.

- Stage 01 framed the problem, stakeholders, and assumptions.
- Stage 02 sets up a reproducible repo and environment for the pipeline.

## Repo Structure
```
data/            # data storage
  raw/           # raw inputs (CSV, etc.)
  processed/     # cleaned/processed data
src/             # Python modules
notebooks/       # Jupyter notebooks
docs/            # project memos, reports
.gitignore       # ignores secrets/system clutter
requirements.txt # Python dependencies
Makefile         # automation shortcuts
README.md        # project overview
```

## Setup Instructions
1. Clone the repo via SSH:
   ```bash
   git clone git@github.com:muideenn/nyufoundationsofmachinelearning_project.git
   cd nyufoundationsofmachinelearning_project
   ```
2. Create a virtual environment and install requirements:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```
3. Launch Jupyter:
   ```bash
   make notebook
   ```

## Lifecycle Progress
- Stage 01 → Problem framing, memo, repo plan
- Stage 02 → Tooling setup, version control, reproducible environment
- Stage 03 → Data acquisition & ingestion (next)
