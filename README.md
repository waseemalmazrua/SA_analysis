🔍 Emergency Incident Analysis: Saudi Regions (2024-2025)

This project analyzes public health emergency reports from 13 regions in Saudi Arabia, based on 2024-2025 data from the Saudi Open Data platform.

📊 Dataset Overview

The merged dataset combines:

accidents.csv → road traffic incident reports

drowning.csv → reported drowning cases

sob.csv → shortness of breath cases

Each file includes:

Region name

Yearly count of incidents

⚖️ Objectives

Calculate total and proportional distribution of incidents

Identify which type is most dominant in each region

Visualize trends using bar charts

Provide actionable insights for public health and traffic safety planning

📝 Key Columns

Column

Description

region

Region name

accidents

# of traffic accident reports

drowning

# of drowning cases

sob

# of shortness of breath incidents

total

Sum of all three types

pct_accidents

Proportion of traffic accidents per region

pct_drowning

Proportion of drowning cases per region

pct_sob

Proportion of SOB incidents per region

dominant_type

Most frequent incident type in the region

📈 Visualizations

Bar chart: Top 3 regions per incident type

Stacked chart: Comparison by proportions

🚀 Tech Stack

Python (Pandas, NumPy, Matplotlib)

Jupyter Notebook

✅ Usage

Clone the repository

Open readmission.ipynb in JupyterLab

Run all cells to reproduce analysis

📁 Files


readmission.ipynb → Final notebook

README.md → Project overview

💪 Author

Waseem Almazrua


### Sources:
1- total road traffic accidents: https://open.data.gov.sa/en/datasets/view/23d1fe79-9d33-4e89-bef4-a4796e4261cb

2- total cases of shortness of breath: https://open.data.gov.sa/en/datasets/view/a80945a5-014c-4113-9c1e-2bdb9e938ce5

3- total cases of drowning: https://open.data.gov.sa/en/datasets/view/e59b6c45-4b33-4bb5-adf7-c457c48e1d88
