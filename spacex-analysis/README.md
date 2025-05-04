# Applied-Data-Science-Capstone

SpaceX Launch Analysis: Data Science Insights and Predictive Modeling


├── notebooks/               # Jupyter notebooks for data analysis and modeling
│   ├── data_collection.ipynb
│   ├── data_wrangling.ipynb
│   ├── eda.ipynb
│   └── predictive_modeling.ipynb
├── scripts/                 # Python scripts for automation and deployment
│   ├── data_cleaning.py
│   └── dashboard_app.py
├── data/                    # Raw and processed datasets
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── presentation.pdf          # Final presentation summarizing the project
├── README.md                 # This file
└── requirements.txt          # List of Python dependencies

Project Overview
This repository contains the code, datasets, and documentation for the final capstone project of the Applied Data Science course on Coursera. The project focuses on analyzing SpaceX launch data to uncover insights into mission success rates, payload trends, geospatial patterns, and predictive modeling of future launches.

The analysis includes:

Data Collection : Using APIs and web scraping techniques.
Exploratory Data Analysis (EDA) : Visualizing trends and patterns in the data.
Predictive Modeling : Building machine learning models to predict launch outcomes.
Interactive Dashboards : Creating interactive maps and dashboards using Plotly Dash and Folium.
Objectives
The main objectives of this project are:

To analyze historical SpaceX launch data and identify key factors influencing mission success.
To build predictive models that forecast the probability of successful launches.
To create interactive visualizations and dashboards for better data interpretation.
To document the entire data science workflow for reproducibility and collaboration.
Data Collection
The dataset used in this project was collected from the SpaceX API and enriched with additional data from web scraping. Key attributes include:

Launch date, time, and location.
Payload mass and orbit type.
Mission success/failure status.
Landing pad and recovery details.
For more details, refer to the data collection notebook .

Methodology
The project follows a structured data science workflow:

Data Cleaning and Wrangling : Handling missing values, removing duplicates, and transforming raw data into a usable format.
Exploratory Data Analysis (EDA) : Analyzing trends, correlations, and patterns using statistical methods and visualizations.
Predictive Modeling : Training and evaluating classification models to predict launch success.
Visualization : Creating interactive maps, dashboards, and plots to communicate findings effectively.
Key Findings
Some of the key insights uncovered during the analysis include:

Trends in launch success rates over time.
Correlations between payload mass and mission outcomes.
Geospatial patterns of launch sites and landing pads.
Predictive model accuracy and feature importance.
