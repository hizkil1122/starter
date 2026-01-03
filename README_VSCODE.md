# VS Code Quickstart

Steps to use this project in Visual Studio Code:

1. Open this folder in VS Code (`File → Open Folder...`).
2. Create a virtual environment (PowerShell):

```powershell
python -m venv .venv
.\.venv\Scripts\python -m pip install -U pip
.\.venv\Scripts\python -m pip install -r requirements.txt
```

3. Select the interpreter: `Ctrl+Shift+P` → `Python: Select Interpreter` → pick the `.venv` entry.
4. Run tests: Use the Test Explorer or run the `Run Tests` task (Terminal → Run Task → `Run Tests`).
5. Debug: Open `main.py` and use the `Python: Current File` configuration, or run `Python: Pytest` to debug tests.

Files added for VS Code support:

- `.vscode/settings.json` — workspace settings (pytest enabled)
- `.vscode/launch.json` — debug configurations
- `.vscode/tasks.json` — quick task to run tests
- `.vscode/extensions.json` — recommended extensions
