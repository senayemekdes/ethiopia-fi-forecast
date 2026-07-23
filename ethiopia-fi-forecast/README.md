# Ethiopia Financial Inclusion Forecasting

A forecasting system for Ethiopia's Access (account ownership) and Usage
(digital payment adoption) financial inclusion indicators, built for Selam
Analytics.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # on Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Project Structure

See `data/raw/` for source data, `notebooks/` for analysis, `src/` for
reusable code, `dashboard/app.py` for the Streamlit app, `models/` for
saved model artifacts, and `reports/` for write-ups and figures.

## Running the Dashboard

```bash
streamlit run dashboard/app.py
```

## Tasks

1. Data Exploration & Enrichment
2. Exploratory Data Analysis
3. Event Impact Modeling
4. Forecasting
5. Dashboard
