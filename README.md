# LLM in Production

A professional monorepo for practical and theoretical LLM practices, covering the entire lifecycle from fundamentals to deployment.

## Repository Structure

This repository is organized into several key directories, each representing a stage of the LLM development process.

### 1. `nlp_lib/` - Fundamentals & Research
Core NLP components and theoretical explorations.
- `src/`: Reusable Python code for text preprocessing, tokenizers, etc.
- `notebooks/`: Jupyter notebooks for foundational NLP concepts.

### 2. `data/` - Data Management
All data-related scripts and files.
- `raw/`: Untouched datasets.
- `processed/`: Cleaned and ready-for-training data.
- `.gitignore`: Ensures large files are not committed.

### 3. `llm_training/` - Models & Training
The heart of model development and finetuning.
- `src/`: Custom model wrappers, trainers, and training utilities.
- `configs/`: YAML configurations for each training run.
- `experiments/`: Tracked experiments with logs and metrics.
- `artifacts/`: Checkpoints and adapters from training.

### 4. `llm_serving/` - Serving & Deployment
Code for deploying models as a service.
- `src/`: FastAPI/Flask application logic for inference.
- `docker/`: Dockerfiles and compose files for reproducible environments.
- `configs/`: Configuration for the serving application.

### 5. `tools/` - Shared Utilities
Common code that is shared across all subprojects.

## Getting Started

To set up the project, you can use `pyproject.toml` and a package manager like `Poetry` or `uv`.# LLMs_Engineering
