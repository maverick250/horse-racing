# Predicting Horse Race Outcomes Using Machine Learning

This repository documents the development and evaluation of machine learning models aimed at predicting whether a horse will finish among the top three in a race. By leveraging extensive data preprocessing, feature engineering, and a variety of classifiers, including Random Forest, Multi-Layer Perceptron, XGBoost, and a Voting Classifier, this project explores the potential of data-driven approaches to enhance race outcome predictions.

## Project Overview

- **Objective:** Predict if a horse will finish in the top three positions (is_top3) using machine learning.
- **Approaches:**  
  - **Data Preprocessing & Feature Engineering:** Transform raw horse racing data into useful features.
  - **Modeling Techniques:** Experiment with Random Forest, Multi-Layer Perceptron, XGBoost, and ensemble methods.
- **Key Finding:**  
  - The Random Forest classifier achieved the best performance with a ROC-AUC of 0.79, demonstrating its suitability for this task.
- **Applications:**  
  - Informing betting strategies, optimizing training, and aiding race planning decisions.

## Repository Structure

```bash
horse-racing/
├── README.md                   # This file.
├── cleaned_race_details.csv    # Processed race details.
├── cleaned_race_results.csv    # Processed race outcomes.
├── eda.ipynb                   # Exploratory Data Analysis notebook.
├── model_development.ipynb     # Notebook for model training and evaluation.
└── report.pdf                  # Detailed technical report.
```

*Note: The report provides a comprehensive overview of the methodology, including background, problem statement, experimental setup, and evaluation metrics.*

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your_username/horse-racing.git
   cd horse-racing```

## Explore the Notebooks

- Open `eda.ipynb` for exploratory data analysis.
- Open `model_development.ipynb` for insights into model development and performance evaluation.
- Launch these using Jupyter Notebook or JupyterLab.

## Documentation and Report

For a detailed account of the project, including the methodology and comprehensive results, please refer to the technical report:

- [View Report (PDF)](report.pdf)

## Excerpts from the Report

### Abstract

This report presents the development and evaluation of machine learning models for predicting horse race outcomes, specifically whether a horse finishes in the top three positions. By utilizing extensive data preprocessing, feature engineering, and multiple modeling approaches, several classifiers were trained and tested, including Random Forest, Multi-Layer Perceptron, XGBoost, and a Voting Classifier. The Random Forest model demonstrated the best performance with a ROC-AUC of 0.79, suggesting its suitability for this prediction task. The study explores the influence of various factors, including historical performance metrics and race-specific conditions, highlighting their roles in determining race results. Limitations such as data quality, feature exclusion, and model interpretability are discussed, along with potential avenues for future improvements.

### Introduction

Horse racing is a prominent sport with a global following, attracting significant attention from enthusiasts, bettors, and industry stakeholders alike. Predicting race outcomes, particularly identifying the top three finishers, holds substantial value in various applications such as betting strategies, training optimizations, and race planning. Traditional prediction methods often rely on expert judgment and historical trends; however, these approaches may not fully capture the complex interplay of multiple variables. With the advent of machine learning, it is now possible to analyze large datasets to uncover hidden patterns by leveraging features like horse attributes, jockey performance, and track conditions. This project focuses on developing robust predictive models using such data-driven techniques.
