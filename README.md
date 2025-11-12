# solar-challenge-week0

This repository contains the work for the 10 Academy "Solar Challenge — Week 0" training (KAIM).

Contents
- `notebooks/` — exploratory notebooks for countries (Benin, Togo, Sierra Leone) and comparison notebooks.
- `data/` — (expected) place for CSV datasets used by the notebooks (sierraleone.csv, benin.csv, togo.csv).
- `src/` — supporting code and scripts.
- `requirements.txt` — pinned Python dependencies used for the environment.

Quick start (Windows, PowerShell)

1. Create a virtual environment (if not already created):

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

2. Upgrade packaging tools and install dependencies:

```powershell
python -m pip install --upgrade pip setuptools wheel
python -m pip install -r requirements.txt
```

Running the notebooks

- Open VS Code or Jupyter after activating the virtual environment. In VS Code use the Python interpreter inside `venv\Scripts\python.exe` (the workspace `.vscode/settings.json` already points to it).
- Launch the notebook UI (e.g., `jupyter lab` or open the `.ipynb` files in VS Code) and run cells from the top.
