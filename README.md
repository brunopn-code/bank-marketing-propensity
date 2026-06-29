# Bank Marketing Propensity Analytics

## Project Overview

This portfolio project analyzes a bank marketing campaign dataset and builds a machine learning model to predict whether a client is likely to subscribe to a term deposit.

The goal is to combine exploratory data analysis, classification modeling, model evaluation, and business recommendations.

## Business Problem

Banks often contact clients through marketing campaigns, but contacting every client has a cost. A better targeting strategy can help increase campaign efficiency by focusing on clients with a higher probability of responding positively.

This project uses marketing campaign data to answer:

1. Which client and campaign characteristics are associated with subscription?
2. What factors are most useful for predicting campaign success?
3. Can a machine learning model help prioritize clients for future campaigns?
4. How should model performance be evaluated from a business perspective?

## Dataset

This project will use the **UCI Bank Marketing dataset**, which contains data from direct marketing campaigns of a Portuguese banking institution.

The target variable is:

```text
y
```

where:

* `yes` means the client subscribed to a term deposit
* `no` means the client did not subscribe

## Important Modeling Note

The dataset includes a variable called `duration`, which represents the duration of the last contact with the client.

This variable is highly predictive, but it is only known after the call has happened. For realistic pre-campaign targeting, the project will compare:

1. a model including `duration`
2. a model excluding `duration`

The second model is more realistic for identifying clients before contacting them.

## Repository Structure

```text
bank-marketing-propensity/
│
├── data/
│   ├── raw/
│   └── sample/
│
├── notebooks/
│   ├── 01_data_preparation.ipynb
│   ├── 02_exploratory_analysis.ipynb
│   └── 03_modeling.ipynb
│
├── src/
├── images/
├── models/
├── dashboard/
├── requirements.txt
└── README.md
```

## Tools Planned

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* DuckDB or SQL-style analysis
* Streamlit or dashboarding

## Planned Analysis

The project will include:

1. Data loading and preparation
2. Exploratory data analysis
3. Target distribution and class imbalance analysis
4. Client profile analysis
5. Campaign performance analysis
6. Baseline classification model
7. Logistic Regression, Random Forest, and Gradient Boosting comparison
8. Model evaluation using precision, recall, F1-score, ROC-AUC, and confusion matrix
9. Feature importance analysis
10. Business recommendations

## Portfolio Purpose

This project is part of my data portfolio and is designed to demonstrate:

* applied machine learning
* classification modeling
* business-oriented model evaluation
* customer propensity analysis
* feature interpretation
* data storytelling
