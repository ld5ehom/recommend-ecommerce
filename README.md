# Improving Product Recommendation for Churn Prevention in E-commerce

## Project Overview

**E-commerce Product Recommendation & Churn Prediction**

-   Designed an embedding based search retrieval system with item query embeddings and ANN to improve product discovery efficiency.
-   Built a PyTorch Item2Vec model for similar item recommendation as well as co purchase filtering and recently viewed product ranking to enhance personalization.
-   Implemented category based filtering and banner optimization with multi armed bandit to deliver targeted promotions and diverse recommendation strategies.
-   Developed churn prediction models using Logistic Regression and Random Forest to identify at risk customers and designed retention strategies with measurable business impact.
-   Technologies: Python, PyTorch, TensorFlow, Scikit learn, Pandas, Numpy, ANN Search, Multi armed Bandit

---

## Problem Statement

E-commerce platforms face two challenges:

1. Helping customers discover relevant products efficiently.
2. Preventing customer churn that reduces long-term revenue.

While recommendation systems improve personalization and short-term engagement, they often overlook churn risk, leading to lost sales and higher acquisition costs.

---

## Project Idea

This project integrates recommendation system improvement with churn prediction modeling to strengthen both personalization and retention.  
It enhances product search and ranking modules for better engagement while applying predictive models to proactively reduce churn and increase customer lifetime value (LTV).

---

## System Overview (Pipeline)

1. **Data Exploration**

    - Analyzed product catalogs, transaction logs, and customer histories.
    - Defined churn and compared churned vs. retained customer behavior (EDA on demographics, transaction patterns, product usage).

2. **Recommendation Modules**

    - Embedding-based search retrieval (item–query embeddings with ANN retrieval)
    - Similar item recommendation trained via PyTorch Item2Vec (skip-gram with negative sampling)
    - Category-based filtering using item metadata for constrained discovery
    - Multitask neural network predicting click, add-to-cart, and purchase to optimize downstream ranking
    - Co-purchase recommendation
    - Recently viewed and related ranking
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

-   Improved recommendation modules for personalization and engagement, with new deep learning–based embedding and multitask learning architectures integrated into the system.
-   Combined traditional collaborative signals (co-purchase, recently viewed) with embedding similarity and category filters for more diverse recommendation strategies.
-   Built churn prediction models to identify at-risk customers early.
-   Random Forest achieved better recall and AUC, making it more practical for churn prevention.
-   High-risk customers tend to show low transaction activity, older age, and lower card categories.
-   The project demonstrates that combining recommendation systems with churn modeling enables data-driven strategies for both growth and retention in e-commerce.

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
