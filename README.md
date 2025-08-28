# Containerized ETL Pipeline with Prefect and PostgreSQL
A minimal, containerized ETL pipeline scaffold using Prefect for orchestration and PostgreSQL for local storage. It’s designed to be easy to spin up with Docker, easy to extend with your own flows, and simple to test locally with Poetry/pytest.

Tech stack:
- Python (managed with Poetry)
- Prefect (orchestration & scheduling)
- PostgreSQL (local persistent store)
- Docker & Docker Compose (runtime)
- Pytest (tests)
- GitHub Actions (CI hooks under .github/workflows/)

Prerequisites
- Docker & Docker Compose
- Python 3.11+ (for local runs without Docker)
- Poetry (pipx install poetry or see poetry docs)
