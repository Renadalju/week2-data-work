# week2-data-work

Week 2 data work project for loading, cleaning, and analyzing order data.

---

## Requirements
- Python 3.11+
- uv (fast Python package & environment manager)

---

## Create the Environment & Install Dependencies (uv sync)

1) Open a terminal in the project root (where `pyproject.toml` is located):

```bash
cd week2-data-work

---

2) 
```bash
uv sync

---

3) Use uv run to execute Python inside the managed environment (no manual activation needed):
```bash
uv run python scripts/run_day1_load.py
uv run python scripts/run_day2_clean.py
uv run python scripts/run_day3_build_analytics.py

---

## Jupyter Notebooks

### Running Notebooks with uv
1) start jypter using :
```bash 
uv run jupyter lab

---
2) then open the file located at week2-data-work\notebooks\eda.ipynb
