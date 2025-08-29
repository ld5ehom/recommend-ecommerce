# Improving Product Recommendation for Churn Prevention in E-commerce

## Project Overview

-   Implemented product recommendation modules including item–query embedding-based search retrieval, similar item ranking, co-purchase filtering, recently viewed & related ranking, category-based suggestions, and banner optimization with multi-armed bandit.
-   Enhanced product discovery and personalization through embedding-based retrieval and ranking strategies.
-   Defined churn behavior in the e-commerce context and conducted exploratory analysis to identify differences between churned and retained customers (e.g., transaction frequency, card type, income category).
-   Built binary classification models (Logistic Regression, Random Forest) to predict churn risk and evaluated performance with accuracy, precision, recall, and AUC.
-   Derived retention strategies from churn drivers (e.g., low transaction activity, high age group, low card category) and simulated potential revenue impact through targeted campaigns.

---

## Problem Statement

E-commerce platforms face two challenges:

1. Helping customers discover relevant products efficiently.
2. Preventing customer churn that reduces long-term revenue.

While recommendation systems improve personalization and short-term engagement, they often overlook churn risk, leading to lost sales and higher acquisition costs.

---

## Project Idea

This project integrates **recommendation system improvement** with **churn prediction modeling** to strengthen both personalization and retention.  
It enhances product search and ranking modules for better engagement while applying predictive models to proactively reduce churn and increase customer lifetime value (LTV).

---

## System Overview (Pipeline)

1. **Data Exploration**

    - Analyzed product catalogs, transaction logs, and customer histories.
    - Defined churn and compared churned vs. retained customer behavior (EDA on demographics, transaction patterns, product usage).

2. **Recommendation Modules**

    - Embedding-based search retrieval (implemented with item–query embeddings and ANN-based retrieval)
    - Similar item recommendation
    - Co-purchase recommendation
    - Recently viewed & related ranking
    - Category-based recommendation
    - Banner optimization with multi-armed bandit

3. **Churn Prediction Modeling**

    - Trained Logistic Regression and Random Forest models.
    - Evaluated performance using precision, recall, accuracy, and AUC.

4. **Model Evaluation**

    - Random Forest outperformed Logistic Regression with higher AUC and recall.
    - Recall emphasized as a business priority to avoid missing at-risk customers.

5. **Retention Strategy & Actionable Insights**
    - Identified churn drivers (low transaction activity, higher age group, low card category).
    - Defined high-risk customers with churn probability ≥ 0.7.
    - Proposed targeted retention actions such as personalized campaigns, loyalty benefits, and proactive engagement.
    - Simulated potential business impact of interventions.

---

## Summary

-   Improved recommendation modules for personalization and engagement.
-   Built churn prediction models to identify at-risk customers early.
-   Random Forest achieved better recall and AUC, making it more practical for churn prevention.
-   High-risk customers tend to show low transaction activity, older age, and lower card categories.
-   The project demonstrates that **combining recommendation systems with churn modeling** enables data-driven strategies for both growth and retention in e-commerce.

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
