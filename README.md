# Improving Product Recommendation for Churn Prevention in E-commerce

## Project Overview

-   Implemented product recommendation modules including embedding-based search, similar item ranking, co-purchase filtering, recently viewed & related ranking, category-based suggestions, and banner optimization with multi-armed bandit.
-   Enhanced product discovery and personalization through embedding-based retrieval and ranking strategies.
-   Defined churn behavior in the e-commerce context and conducted exploratory analysis to identify differences between churned and retained customers (e.g., transaction frequency, card type, income category).
-   Built binary classification models (Logistic Regression, Random Forest, XGBoost) to predict churn risk and evaluated performance with accuracy, precision, recall, and AUC.
-   Derived retention strategies from churn drivers (e.g., low transaction activity, specific customer segments) and simulated potential revenue impact through targeted campaigns.

---

## Problem Statement

E-commerce platforms face two challenges:

1. Helping customers discover relevant products efficiently.
2. Preventing customer churn that reduces long-term revenue.

While recommendation systems improve personalization and short-term engagement, they often overlook churn risk, leading to lost sales and higher acquisition costs.

---

## Project Idea

The project integrates product recommendation improvements with churn prediction analysis to strengthen both personalization and retention.  
It enhances product search and ranking modules for better engagement, while applying churn modeling techniques to proactively reduce attrition and improve customer lifetime value.

---

## System Overview (Pipeline)

1. Data Exploration

    - Analyze product catalogs, transaction logs, and customer histories.
    - Define churn and compare churn vs. retained customer behavior (EDA on demographics, transaction patterns, product usage).

2. Recommendation Modules

    - Embedding-based search retrieval
    - Similar item recommendation
    - Co-purchase recommendation
    - Recently viewed & related ranking
    - Category-based recommendation
    - Banner optimization with multi-armed bandit

3. Churn Prediction Modeling

    - Train classification models to identify churn risk.
    - Evaluate performance with precision, recall, accuracy, and AUC.

4. Retention Strategy

    - Identify churn drivers through statistical analysis and EDA.
    - Propose targeted retention actions and estimate business impact with scenario simulations.

---

## Setup

```
python -m venv venv
```

```
source venv/bin/activate
```

```
pip install -r requirements.txt
```

---

## Start

```
source venv/bin/activate
```

---

## Save Requirement.txt

```
pip freeze > requirements.txt
```
