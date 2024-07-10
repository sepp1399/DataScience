# Repository Analysis

This repository contains three files, each performing different analyses on`healthcare-dataset-stroke-data.csv` dataset. Below is a detailed description of each file and the analyses performed within.

## Files Overview

1. `cigarette_smoking_TAI.ipynb`
2. `cygarette_smoking.ipynb`
3. `healthcare-dataset-stroke-data.csv`

### 1. `cigarette_smoking_TAI.ipynb`

This Jupyter Notebook contains an analysis of cigarette smoking data using Trustworthy AI (TAI) methods. The primary goals of this analysis are to:

- Examine trends in cigarette smoking over a specified period.
- Calculate the Trustworthy AI metrics to understand the rate of smoking initiation in different age groups.
- Use visualizations to represent the smoking trends and TAI calculations effectively.

#### Key Steps:
- **Data Loading and Preprocessing:** Load the dataset and handle any missing or inconsistent data.
- **TAI Calculation:** Calculate the Trustworthy AI metrics for different age groups.
- **Data Visualization:** Create plots to visualize the smoking trends and TAI results.

### 2. `cygarette_smoking`

This notebook includes various analyses and exercises designed to test their understanding of data analysis techniques and tools.

#### Key Analyses:
- **Exploratory Data Analysis (EDA):** Perform EDA on a given dataset to identify patterns, outliers, and important statistics.
- **Data Visualization:** Create visualizations to support findings from the EDA.
- **Statistical Analysis:** Conduct hypothesis testing or other statistical analyses as required by the examination.
- **Machine Learning:** Apply machine learning models to predict outcomes based on the dataset.

### 3. `healthcare-dataset-stroke-data.csv`

This CSV file contains data related to stroke incidents in a healthcare setting. The dataset includes various attributes such as age, gender, hypertension, heart disease, and more.

#### Key Columns:
- `id`: Unique identifier for each patient.
- `gender`: Gender of the patient.
- `age`: Age of the patient.
- `hypertension`: Whether the patient has hypertension.
- `heart_disease`: Whether the patient has heart disease.
- `ever_married`: Marital status of the patient.
- `work_type`: Type of work the patient does.
- `Residence_type`: Type of residence the patient lives in.
- `avg_glucose_level`: Average glucose level of the patient.
- `bmi`: Body mass index of the patient.
- `smoking_status`: Smoking status of the patient.
- `stroke`: Whether the patient had a stroke.

This dataset can be used for predictive analysis to identify factors contributing to stroke incidents and to develop models for predicting stroke risk.

## Getting Started

To run the analyses provided in the Jupyter Notebooks, follow these steps:

1. Ensure you have Python installed on your system.
2. Install the required libraries by running:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

