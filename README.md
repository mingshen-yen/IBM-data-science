# IBM Data Science (Notebooks)

This repository contains Jupyter Notebook work from the IBM Data Science curriculum, including a capstone-style project based on the SpaceX Falcon 9 launch dataset.

## Repository structure

- `final_assignment/`  
  Capstone deliverables and supporting assets:
  - Data collection notebooks (API + web scraping)
  - Data wrangling and exploratory analysis (including SQL + visualization)
  - Interactive dashboard notebook
  - Geospatial/launch site analysis notebook(s)
  - Machine learning notebook for launch outcome prediction
  - CSV datasets and a `requirements.txt`

- `HandonLab_EcoSystem/`  
  Additional hands-on lab materials (notebooks).

## Notebooks (high level)

Inside `final_assignment/` you’ll find notebooks such as:
- **Data collection**: SpaceX API, web scraping
- **Data wrangling**: cleaning, transforming, feature engineering
- **EDA**: visualization + SQL-based exploration
- **Dashboard**: interactive exploration (commonly Plotly Dash in this project track)
- **Machine learning**: classification models to predict landing success

## Getting started

### Option A — View on GitHub
You can browse and render the notebooks directly in GitHub.

### Option B — Run locally

1. Clone the repo:
   ```bash
   git clone https://github.com/mingshen-yen/IBM-data-science.git
   cd IBM-data-science
   ```

2. (Recommended) Create and activate a virtual environment.

3. Install dependencies (capstone requirements are in `final_assignment/requirements.txt`):
   ```bash
   pip install -r final_assignment/requirements.txt
   ```

4. Launch Jupyter:
   ```bash
   jupyter lab
   ```
   or
   ```bash
   jupyter notebook
   ```

## Data

The `final_assignment/` folder includes several CSV files used by the notebooks (e.g., intermediate datasets and dashboard inputs). These are intended for learning/demo purposes as part of the course project.

## License

See `final_assignment/LICENSE` (if applicable). If you want a single repo-wide license, consider adding a top-level `LICENSE` file.

---
**Author:** mingshen-yen  
**Repo:** https://github.com/mingshen-yen/IBM-data-science
