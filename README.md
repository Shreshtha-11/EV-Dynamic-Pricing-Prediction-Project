# Agentic AI Based Dynamic Tariff Optimization for EV Charging Networks
Open Project 2026 · Society of Business

## Dataset Setup
The datasets are not included in this repository as they were provided via the competition Google Drive.

Before running the notebooks, create the following folder structure and place the files accordingly:

data/
├── raw/
│   ├── acn/
│   │   └── acndata_sessions.json.xlsx
│   └── st_evcdp/
│       ├── occupancy.csv
│       ├── volume.csv
│       ├── duration.csv
│       ├── price.csv
│       ├── time.csv
│       └── stations.csv

## Setup
1. Create a virtual environment: `python -m venv venv`
2. Activate it: `venv\Scripts\activate` (Windows) or `source venv/bin/activate` (Mac/Linux)
3. Install dependencies: `pip install -r requirements.txt`

## Running the Notebooks
Run in order:
1. `01_data_preprocessing.ipynb`
2. `02_eda_findings.ipynb`
3. `03_demand_prediction_agent.ipynb`
4. `04_tariff_pricing_agent.ipynb`
5. `05_monitoring_learning_agent.ipynb`

## Outputs
All results are saved automatically to:
- `outputs/csvs/` — metric scores and evaluation results
- `outputs/plots/` — all visualizations
