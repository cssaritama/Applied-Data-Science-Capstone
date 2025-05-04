# SpaceX Launch Analysis: Data Science Insights and Predictive Modeling

![SpaceX Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/SpaceX-Logo.svg/1200px-SpaceX-Logo.svg.png)

## Table of Contents
1. [Project Overview](#project-overview)
2. [Objectives](#objectives)
3. [Data Collection](#data-collection)
4. [Methodology](#methodology)
5. [Key Findings](#key-findings)
6. [Repository Structure](#repository-structure)
7. [Tools and Libraries](#tools-and-libraries)
8. [How to Run the Code](#how-to-run-the-code)
9. [Contributions](#contributions)
10. [License](#license)

---

### **Project Overview**
This repository contains the code, datasets, and documentation for the final capstone project of the **Applied Data Science Specialization** course on Coursera. The project is part of a guided lab provided by Coursera and focuses on analyzing SpaceX launch data to uncover insights into mission success rates, payload trends, geospatial patterns, and predictive modeling of future launches.

The analysis includes:
- **Data Collection**: Using APIs and web scraping techniques.
- **Exploratory Data Analysis (EDA)**: Visualizing trends and patterns in the data.
- **Predictive Modeling**: Building machine learning models to predict launch outcomes.
- **Interactive Dashboards**: Creating interactive maps and dashboards using Plotly Dash and Folium.

This project is intended for educational purposes and demonstrates the application of data science techniques to real-world datasets.

---

### **Objectives**
The main objectives of this project are:
1. To analyze historical SpaceX launch data and identify key factors influencing mission success.
2. To build predictive models that forecast the probability of successful launches.
3. To create interactive visualizations and dashboards for better data interpretation.
4. To document the entire data science workflow for reproducibility and collaboration.

---

### **Data Collection**
The dataset used in this project was collected from the **SpaceX API** and enriched with additional data from web scraping. Key attributes include:
- Launch date, time, and location.
- Payload mass and orbit type.
- Mission success/failure status.
- Landing pad and recovery details.

For more details, refer to the [data collection notebook](notebooks/data_collection.ipynb).

---

### **Methodology**
The project follows a structured data science workflow:
1. **Data Cleaning and Wrangling**: Handling missing values, removing duplicates, and transforming raw data into a usable format.
2. **Exploratory Data Analysis (EDA)**: Analyzing trends, correlations, and patterns using statistical methods and visualizations.
3. **Predictive Modeling**: Training and evaluating classification models to predict launch success.
4. **Visualization**: Creating interactive maps, dashboards, and plots to communicate findings effectively.

---

### **Key Findings**
Some of the key insights uncovered during the analysis include:
- Trends in launch success rates over time.
- Correlations between payload mass and mission outcomes.
- Geospatial patterns of launch sites and landing pads.
- Predictive model accuracy and feature importance.

For detailed results, refer to the [presentation PDF](presentation.pdf) and the [EDA notebook](notebooks/eda.ipynb).

---

### **Repository Structure**
The repository is organized as follows:

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

---

### **Tools and Libraries**
The following tools and libraries were used in this project:
- **Programming Language**: Python
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly, Folium
- **Machine Learning**: Scikit-learn
- **Web Scraping**: BeautifulSoup, Requests
- **Dashboards**: Plotly Dash
- **API Integration**: SpaceX API

To install the required libraries, run:
```bash
pip install -r requirements.txt
