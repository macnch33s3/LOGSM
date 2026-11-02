# LOGSM

Time-series forecasting exercise on historical beer demand data, implemented in Jupyter notebooks.

## Contents

| File | Description |
|---|---|
| `2_Exercise_Forecasting_Code.ipynb` | Original forecasting exercise notebook |
| `2_Exercise_Forecasting_Code_revamped.ipynb` | Revised version of the exercise |
| `Historical Data Beerdemand.xlsx` | Historical demand dataset used by the notebooks |
| `main.py` | Entry point (placeholder) |
| `pyproject.toml` / `uv.lock` | Project metadata and locked dependencies |
| `.python-version` | Pinned Python version |

## Setup

Requires [uv](https://docs.astral.sh/uv/).

```bash
git clone https://github.com/macnch33s3/LOGSM.git
cd LOGSM
uv sync
```

## Usage

Start Jupyter and open one of the notebooks:

```bash
uv run jupyter lab
```

The notebooks expect `Historical Data Beerdemand.xlsx` in the repository root.

## License

tbd
