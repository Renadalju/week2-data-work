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
```



2) then:
```bash
uv sync
```


---



## If you want to run the pipeline on NEW data:

### A) Add your new raw data
Place your files in the raw data folder:

- `data/raw/users.csv`
- `data/raw/orders.csv`

> Make sure the filenames match exactly, because the scripts expect these paths.

### B) (Optional) Generate sample data
If you want to generate a fresh dataset automatically:
```bash
uv run python scripts/generate_data.py
```

### C) Run the pipeline scripts in order
``` bash
uv run python scripts/run_day1_load.py
uv run python scripts/run_day2_clean.py
uv run python scripts/run_day3_build_analytics.py
```


---


## Jupyter Notebooks

### Running Notebooks with uv
1) start jypter using :
```bash 
uv run jupyter lab notebooks 
```
2) Follow the instructions and run 

