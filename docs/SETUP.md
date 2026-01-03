# Setup Guide

## Prerequisites

- Python 3.8 or higher
- pip (included with Python)
- Git

## Development Setup

### 1. Clone the Repository

```bash
git clone https://github.com/hizkil1122/starter.git
cd starter
```

### 2. Create a Virtual Environment

**On Windows (PowerShell):**
```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

**On macOS/Linux:**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -U pip
pip install -r requirements.txt
```

### 4. Verify Installation

Run the tests to verify everything is working:

```bash
pytest -q
```

## Using in VS Code

1. Open the project in VS Code
2. Press `Ctrl+Shift+P` and select **Python: Select Interpreter**
3. Choose the `.venv` interpreter
4. Open `main.py` and press `F5` to debug

## Running Tests

```bash
pytest          # run all tests
pytest -v       # verbose output
pytest -q       # quiet output
pytest tests/test_main.py::test_add  # run specific test
```

## Making Changes

Create a new branch for your changes:

```bash
git checkout -b feature/your-feature-name
```

Make your changes, test them, then push:

```bash
git push origin feature/your-feature-name
```

Create a pull request on GitHub.
