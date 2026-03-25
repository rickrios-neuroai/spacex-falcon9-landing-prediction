# SpaceX Falcon 9 Landing Prediction

An end-to-end data science project that analyzes SpaceX Falcon 9 launch data and predicts first-stage landing success using data collection, web scraping, exploratory data analysis, SQL, interactive visualization, and machine learning.

## Project Overview

Reusable rockets reduce launch costs and increase operational efficiency. In this project, I analyzed SpaceX Falcon 9 mission data to identify the main factors associated with first-stage landing success and built classification models to predict landing outcomes.

## Objectives

- Collect launch data from public sources
- Clean and prepare the dataset for analysis
- Explore key variables related to landing success
- Visualize launch patterns, payload effects, and site performance
- Build machine learning models for landing prediction
- Compare model performance and interpret results

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Dash
- Folium
- SQL
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Data collection from API and web scraping sources
2. Data wrangling and feature preparation
3. Exploratory Data Analysis (EDA)
4. SQL-based exploration of launch data
5. Interactive visualizations with Plotly Dash and Folium
6. Machine learning model training and evaluation
7. Final presentation and business-oriented conclusions

## Key Insights

- Launch success rate improved over time
- Payload mass influenced landing success probability
- Launch site selection affected mission outcomes
- Booster reuse was associated with improved performance
- Logistic Regression delivered strong and balanced classification results

## Machine Learning Results

| Model | Accuracy | Precision | Recall |
|---|---:|---:|---:|
| Logistic Regression | 80% | 78% | 82% |
| SVM | 79% | 77% | 80% |
| Decision Tree | 76% | 75% | 77% |
| KNN | 74% | 73% | 75% |

## Repository Structure

```text
spacex-falcon9-landing-prediction/
├── README.md
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_wrangling.ipynb
│   ├── 03_eda_visualization.ipynb
│   ├── 04_sql_analysis.ipynb
│   ├── 05_interactive_dashboard.ipynb
│   └── 06_machine_learning.ipynb
├── data/
│   ├── raw/
│   └── processed/
├── images/
│   ├── cover.png
│   ├── launch_site_analysis.png
│   ├── payload_analysis.png
│   ├── dashboard_preview.png
│   └── folium_map.png
├── presentation/
│   ├── CAPSTONE_SLIDESHOW.pdf
│   └── CAPSTONE_PROJECT.pptx
├── certificates/
│   ├── ibm_data_science_professional_certificate.pdf
│   └── applied_data_science_capstone_certificate.pdf
└── requirements.txt

Business Value

Predicting landing success helps estimate reusability potential and can support more efficient launch planning, cost reduction, and operational decision-making.

About Me

Richard Rios Ortiz
Data Science, AI, Automation, and Robotics Engineer

Contact

GitHub: rickrios-neuroai, riosra2025@gmail.com
