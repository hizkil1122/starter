# Python Starter Project

Minimal starter project with a simple function and tests.

Requirements
- Python 3.8+

Quick start (PowerShell on Windows)

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

Files
- `main.py` — tiny example app
- `tests/test_main.py` — pytest test

If you'd like a different layout (package, CLI, or web starter), tell me which framework.
