# Alcoholic Classification

## Overview

This project is designed to classify whether a person is alcoholic or not based on provided input features. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, and the application of machine learning models. The project workflow, from raw data to model evaluation, is fully implemented in the Jupyter Notebook `src/Main.ipynb`.

## Methodology

1. **Data Collection**: 
   - The dataset contains features such as [list key features here, e.g., "alcohol content, sugar level, pH"] and a target variable for alcohol type classification.
   - The data was loaded and inspected for structure and quality.

2. **Data Preprocessing**:
   - Handled missing values by applying techniques such as mean/mode imputation or removal of invalid entries.
   - Encoded categorical variables using [One-Hot Encoding/Label Encoding].
   - Applied feature scaling using [StandardScaler/MinMaxScaler] to ensure all features were on comparable scales.

3. **Exploratory Data Analysis (EDA)**:
   - Visualized data distributions for numerical features using histograms and boxplots.
   - Analyzed relationships and correlations using heatmaps and scatter plots.
   - Identified outliers and their impact on classification using visualizations.

4. **Feature Engineering**:
   - Selected the most important features using techniques such as RFE, Random Forest, and Logistic Regression.
   - Created new features by combining or transforming existing ones to improve classification accuracy.

## How to Run

Follow these steps to set up and run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/BVishal-Geek/Alcohol-Classification.git
   ```
   ```bash
   cd Alcohol-Classification
   ```
   ```bash
   jupyter notebook src/Main.ipynb
   ```
   or please run the code chunk by chunk. 
   
