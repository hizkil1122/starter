# Python Starter Project

[![Test](https://github.com/hizkil1122/starter/actions/workflows/test.yml/badge.svg)](https://github.com/hizkil1122/starter/actions/workflows/test.yml)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Minimal starter project with a simple function and tests.

## Requirements

- Python 3.8+

## Quick start (PowerShell on Windows)

```powershell
# create virtualenv
python -m venv .venv

# upgrade pip and install test runner
.\.venv\Scripts\python -m pip install -U pip
.\.venv\Scripts\python -m pip install -r requirements.txt

# run tests
.\.venv\Scripts\python -m pytest -q

# run the app
.\.venv\Scripts\python main.py
```

## Files

- `main.py` — tiny example app
- `tests/test_main.py` — pytest test

If you'd like a different layout (package, CLI, or web starter), tell me which framework.
