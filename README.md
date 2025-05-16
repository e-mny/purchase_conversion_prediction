# 🛒 Cart Abandonment Prediction

Predict cart abandonment in a simulated e-commerce scenario and provide an interactive platform for end-users (e.g., product managers, marketers) to explore predictions, analyze metrics, and simulate interventions like discounts or urgency banners.

---

## 🎯 Goal

To predict which users are likely to abandon their cart and empower stakeholders to interact with predictions, explore key metrics, and simulate interventions to improve conversion rates.

---

## 🔍 Key Features

- **Predictive Modeling**: Identify users likely to abandon their cart using behavioral and session data.
- **Interactive Dashboard**: Visualize predictions, key metrics, and simulate interventions.
- **Scenario Simulation**: Test the impact of strategies like discounts, reminders, or urgency banners on cart abandonment rates.

---

## 📈 Learning Outcomes

- Build and evaluate predictive models for cart abandonment.
- Engineer features from session data: product price, time on page, referral source, engagement patterns, etc.
- Use SHAP for model interpretability to explain predictions.
- Simulate and analyze the effectiveness of interventions on user behavior.
- Gain insights into improving the e-commerce conversion funnel.

---

## 🛠 Tech Stack

- **Modeling**: Logistic Regression, Random Forest
- **Interpretability**: SHAP (SHapley Additive exPlanations)
- **Visualization**: Streamlit for interactive dashboards
- **Dataset**: [UCI Online Shoppers Purchasing Intention Dataset](https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset)
- **Languages**: Python

---

## 📁 Repo Structure

```bash
purchase_retention_prediction/
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_shap_analysis.ipynb
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model.py
│   ├── dashboard.py
│   └── utils.py
├── reports/
│   └── figures/
├── requirements.txt
└── README.md
```

---
