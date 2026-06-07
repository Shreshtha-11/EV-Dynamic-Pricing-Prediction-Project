Agentic AI Based Dynamic Tariff Optimization for EV Charging Networks
Open Project 2026 · Society of Business

Dataset Setup
The datasets are not included in this repository as they were provided via the competition Google Drive.

Before running the notebooks, create the following folder structure and place the files accordingly:

data/ ├── raw/ │ ├── acn/ │ │ └── acndata_sessions.json.xlsx │ └── st_evcdp/ │ ├── occupancy.csv │ ├── volume.csv │ ├── duration.csv │ ├── price.csv │ ├── time.csv │ └── stations.csv

Setup
Create a virtual environment: python -m venv venv
Activate it: venv\Scripts\activate (Windows) or source venv/bin/activate (Mac/Linux)
Install dependencies: pip install -r requirements.txt
Running the Notebooks
Run in order:

01_data_preprocessing.ipynb
02_eda_findings.ipynb
03_demand_prediction_agent.ipynb
04_tariff_pricing_agent.ipynb
05_monitoring_learning_agent.ipynb
Outputs
All results are saved automatically to:

outputs/csvs/ — metric scores and evaluation results
outputs/plots/ — all visualizations
