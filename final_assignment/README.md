# Final Assignment — SpaceX Falcon 9 Landing Prediction (IBM Data Science Capstone)

This folder contains my notebooks, datasets, and supporting files for the **IBM Data Science Professional Certificate Capstone** project. The project focuses on collecting SpaceX launch data, performing exploratory analysis and visualization, building an interactive dashboard, and training machine learning models to predict whether a Falcon 9 first stage will successfully land.

## What’s inside

### Notebooks (workflow)
- **Data collection**
  - `spacex-data-collection-api.ipynb` — Collects launch data via API.
  - `spacex-webscraping.ipynb` — Collects launch-related data via web scraping.
- **Data wrangling**
  - `Data Wrangling.ipynb` — Cleans and prepares the dataset for analysis/modeling.
- **Exploratory Data Analysis (EDA)**
  - `eda-dataviz.ipynb` — EDA and visualizations.
  - `EDA SQL.ipynb` — EDA using SQL queries.
- **Geospatial analysis**
  - `launch_site_locations.ipynb` — Maps launch sites and explores geographic factors.
  - `CalculateDistance.ipynb` — Helper notebook for distance calculations used in mapping/analysis.
- **Dashboard**
  - `Dashboard SpaceX Dataset.ipynb` — Interactive dashboard development (Dash).
- **Machine learning**
  - `machine-learning-prediction-spacex.ipynb` — Model training, evaluation, and prediction pipeline.
- **Other / supplemental**
  - `ADGGoogleClass.ipynb` — Additional practice/notes notebook (supporting material).

### Data files (CSV)
- `Spacex.csv`
- `dataset_part_1.csv`, `dataset_part_2.csv`, `dataset_part_3.csv`
- `spacex_launch_dash.csv` — Dataset used for the dashboard.
- `spacex_launch_geo.csv` — Dataset used for geospatial analysis.
- `spacex_web_scraped.csv` — Output from the web scraping step.

### Report / certificate
- `IBM-capstone-coursera.pdf` — Capstone-related PDF artifact.

### Environment / dependencies
- `requirements.txt` — Minimal Python dependencies:
  - pandas, numpy
  - Flask, Dash, gunicorn
  - dash_html_components, dash_core_components

## How to run (local)

### 1) Create a Python environment (recommended)
```bash
python -m venv .venv
# macOS/Linux:
source .venv/bin/activate
# Windows (PowerShell):
# .venv\Scripts\Activate.ps1
```

### 2) Install dependencies
```bash
pip install -r requirements.txt
```

### 3) Open notebooks
```bash
jupyter lab
# or
jupyter notebook
```

> Note: Some notebooks may require additional libraries commonly used in the capstone (e.g., scikit-learn, matplotlib, seaborn, folium). If you encounter an import error, install the missing package via `pip install <package>`.

## Suggested reading order
1. `spacex-data-collection-api.ipynb`
2. `spacex-webscraping.ipynb`
3. `Data Wrangling.ipynb`
4. `eda-dataviz.ipynb` and/or `EDA SQL.ipynb`
5. `launch_site_locations.ipynb` (+ `CalculateDistance.ipynb` if needed)
6. `Dashboard SpaceX Dataset.ipynb`
7. `machine-learning-prediction-spacex.ipynb`

## License
See `LICENSE` in this folder for licensing details.
