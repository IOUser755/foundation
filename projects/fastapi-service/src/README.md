# FastAPI Service - Source

This directory will contain the FastAPI Python microservice implementation.

## Expected Structure

When real code is added, the following should be present:

- `main.py` or equivalent application entry point
- `requirements.txt` or `pyproject.toml` for dependencies
- Test files for pytest

## Expected Tools

- **uvicorn** - ASGI server for running FastAPI
- **ruff** or **flake8** - Python linter
- **pytest** - Testing framework

## Foundation CI Detection

The foundation CI workflow (`.github/workflows/ci.yml`) will automatically detect this as a Python project when:

- A `requirements.txt` file exists in the repository root or project directory, OR
- A `pyproject.toml` file exists

Once detected, CI will:

1. Install dependencies with `pip install -r requirements.txt || true`
2. Run tests with `pytest -q || true`

Both commands use `|| true` to allow soft failures during initial setup.

## Getting Started

(To be added when real code is implemented)
