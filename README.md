# Application of Machine Learning for Predicting Financial Exclusion and Evaluating the Impact of Digital Connectivity on Financial Exclusion

## Repository Overview

This repository contains the datasets, documentation, and source code developed for the research project **"Application of Machine Learning for Predicting Financial Exclusion and Evaluating the Impact of Digital Connectivity on Financial Exclusion."**

The project applies machine learning techniques to identify the determinants of financial exclusion and examines how digital connectivity influences financial inclusion outcomes using data from the World Bank Global Findex Database and related country-level information.

## Repository Contents

| File | Description |
|------|-------------|
| **VariablesDocumentation.xlsx** | Processed variable dictionary containing metadata for the Global Findex variables, including variable names, descriptions, selection status, and documented inclusion and exclusion decisions used during variable selection. |
| **combined_dataset_weight.csv** | Reference dataset created by integrating the World Bank Global Findex Database with the World Bank Country and Lending Groups dataset. This dataset serves as the primary input for the analysis. |
| **DataAnalyticsFinal.py** | Python script containing final data analysis procedures, including data preprocessing, exploratory data analysis, survey-weighted analyses, feature preparation, machine learning model development, and model evaluation for the research questions. |
| **data_compilation_code.py** | Python script used to compile and integrate the source datasets, including merging the Global Findex dataset with the World Bank Country and Lending Groups classification data and generating the combined analytical dataset. |

## Project Objectives

This project aims to investigate the determinants of financial exclusion using a combination of Artificial Intelligence/Machine Learning (AI/ML) techniques and statistical analysis. Specifically, the study seeks to:

- Examine whether there is a significant difference in the level of financial exclusion between underdeveloped and developing economies.
- Develop and evaluate AI/ML models to predict financial exclusion and identify the most influential demographic, socioeconomic, and technological determinants.
- Compare the determinants of financial exclusion across underdeveloped and developing economies to assess whether the factors influencing financial exclusion differ by level of economic development.
- Evaluate the impact of digital connectivity on financial exclusion and determine whether its influence varies between developing and underdeveloped economies.
- Investigate whether digital connectivity has differential effects on financial exclusion within underdeveloped economies, providing evidence for targeted digital infrastructure and financial inclusion policies.
- Compare the predictive performance of multiple machine learning models using standard evaluation metrics.
- Integrate machine learning and statistical methods to combine predictive accuracy with empirical interpretability, thereby supporting evidence-based and context-specific financial inclusion policy recommendations.

## Data Sources

The analysis is based on publicly available data from:

- World Bank Global Findex Database
- World Bank Country and Lending Groups classification dataset

Users should refer to the original data providers for licensing terms and documentation.

## Methodology

The project follows the general workflow below:

1. Data compilation and integration.
2. Feature selection and documentation. 
3. Data cleaning and preprocessing.
4. Exploratory data analysis.
5. Survey-weighted statistical analysis where applicable.
6. Machine learning model training.
7. Model evaluation using Accuracy, Precision, Recall, F1-score, ROC-AUC, and confusion matrices.
8. Interpretation of findings related to financial exclusion and digital connectivity.

## Repository Purpose

This repository is intended to:

- Support reproducibility of the research.
- Document variable selection decisions.
- Enable future extension of the analysis by other researchers.
- Serve as supplementary material accompanying the research project.

## Citation

If you use this repository or build upon this work, please cite the associated research project or publication where appropriate.

## Disclaimer

The datasets included or referenced in this repository are derived from publicly available World Bank resources. The analyses, preprocessing decisions, and machine learning implementations are those of the authors and do not necessarily represent the views of the World Bank.

