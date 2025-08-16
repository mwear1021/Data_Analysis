# Data Analysis

A small collection of beginner-friendly data analysis notebooks and CSV datasets. The notebooks walk through common tasks—loading data, cleaning, sorting/filtering, and simple exploration/visualization—using Python and Jupyter.

## Repository Structure

```
data_analysis/
├─ electric_vehicle_stations.ipynb
├─ occupations.ipynb
├─ sorting_filtering.ipynb
├─ stations.csv
├─ vehicles.csv
├─ wages.csv
```

## Notebooks

- **electric_vehicle_stations.ipynb**  
  Public EV station dataset exploration and basic filtering/sorting/grouping examples.

- **occupations.ipynb**  
  Wage/occupation dataset walkthrough: reading CSVs, simple EDA, and sanity-checks on execution counts/environments.

- **sorting_filtering.ipynb**  
  Focused mini-notebook demonstrating Pandas sorting, filtering, boolean masks, and selecting columns/rows.

## Datasets

- **stations.csv** – Fuel/electric station information (e.g., station name, location, fuel type).  
- **vehicles.csv** – Example vehicle attributes suitable for sorting/filtering demos.  
- **wages.csv** – Sample occupation/wage data used in `occupations.ipynb`.

> These CSVs are for practice and demonstration; schemas may be minimal and for instructional use.

## Getting Started

### Prerequisites
- Python 3.10+  
- Jupyter Notebook or JupyterLab

### Install

```bash
# (optional) create and activate a virtual environment
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS/Linux
source .venv/bin/activate

pip install -U pip
pip install jupyter pandas numpy matplotlib
```

### Run the notebooks

```bash
jupyter notebook
# then open any *.ipynb in the browser
```

## What You’ll Practice

- Reading CSVs with Pandas (`read_csv`)
- Inspecting DataFrames (`head`, `info`, `describe`)
- Selecting, sorting, and filtering data
- Basic plots with Matplotlib
- Light data cleaning and quick EDA patterns

## Reproducibility Tips

- If a notebook shows “execution count” warnings or out-of-order cells, use **Kernel → Restart & Run All** to reproduce results.
- Keep your environment pinned if you need consistent behavior:

```
pandas==2.*
numpy==1.*
matplotlib==3.*
```

## Contributing

Issues and small PRs are welcome—typo fixes, clearer examples, or new beginner-friendly notebooks.

## License

Add your preferred license (e.g., MIT) here.
