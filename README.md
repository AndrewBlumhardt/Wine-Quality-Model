# Wine-Quality-Model
USD Intro to AI project for Team 6, Fall 2024

# Predictive Modeling of 'Vinho Verde' Wine Quality Using ML
# Overview
This repository contains all the code and documentation used for our study on predicting the quality of 'Vinho Verde' wines through machine learning. The project investigates the effectiveness of various machine learning models in classifying and predicting wine quality based on physicochemical properties.

# Project Team
Ian Rebmann - Team Lead, EDA, Model Engineering, Report Formulation
Keith Holder - EDA, Model Engineering, Reporting
Andrew Blumhardt - EDA, Model Engineering, Documentation

# Contents
data/ - Directory containing datasets used in the analyses.
notebooks/ - Jupyter notebooks with full analysis, including EDA, model training, and evaluation.
src/ - Source code for the project, including data preprocessing and modeling scripts.
docs/ - Additional documentation and project reports.
requirements.txt - List of Python dependencies for the project.
Installation
To set up the project environment, follow these steps:

# Clone this repository:

bash
Copy code
git clone [[repository-url](https://github.com/AndrewBlumhardt/Wine-Quality-Model/tree/main)]
cd [Wine-Quality-Model]
Install required Python packages:

Copy code
pip install -r requirements.txt
Open the Jupyter notebooks:

Copy code
jupyter notebook
Navigate to the notebooks/ directory and open the desired notebook to start exploring the analysis.

# Usage
Each notebook in the notebooks/ directory is named according to the part of the analysis it represents, e.g., 01_data_preprocessing.ipynb, 02_exploratory_data_analysis.ipynb, etc. To replicate the study or explore the models, follow the notebooks in sequential order:

Data Preprocessing - Prepares the data for analysis.
Exploratory Data Analysis - Visualizes and explores dataset characteristics.
Model Training and Evaluation - Builds and evaluates machine learning models.
Scripts in src/ can be run to automate parts of the analysis, such as feature engineering or model training.

Results
Our study found that Random Forest and SVM models performed best in predicting wine quality.
Key features influencing wine quality include alcohol content, volatile acidity, and density.
Refer to the docs/ directory for a detailed report and analysis insights.

# Contributing
Contributions to this project are welcome. Please open an issue to discuss proposed changes or submit a pull request.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.

# Contact
For any queries, please open an issue in the repository. Our team will get back to you as soon as possible.


