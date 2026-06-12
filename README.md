# Sample Project

[![CI](https://github.com/Vaibbs/sample-app/actions/workflows/ci.yml/badge.svg)](https://github.com/Vaibbs/sample-app/actions/workflows/ci.yml)

A simple Python project demonstrating:

* Pytest unit testing
* Flake8 linting
* GitHub Actions CI
* Coverage enforcement

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO

python -m venv .venv

# Linux/macOS
source .venv/bin/activate

# Windows
.venv\Scripts\activate

pip install -r requirements.txt
```

## Running Tests

```bash
pytest
```

## Running Tests with Coverage

```bash
pytest --cov=. --cov-report=term-missing
```

## Running Linting

```bash
flake8 .
```

## Continuous Integration

Every push and pull request automatically runs:

* Flake8
* Pytest
* Coverage checks

You can view workflow runs from the badge above or the Actions tab.

## Project Structure

```text
.
├── app.py
├── test_app.py
├── requirements.txt
├── .flake8
├── README.md
└── .github
    └── workflows
        └── ci.yml
```

## License

MIT
