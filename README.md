# 📊 Default Rate Analysis (2020–2021)

## 🚀 Overview

Credit risk analysis focused on default rate behavior over time.  
The project covers data cleaning, exploratory analysis, feature selection, and predictive modeling to understand and anticipate default patterns.

---

## 📊 Key Insights

- Default rate showed abnormal spikes in 2020, likely driven by external factors
- Models present temporal instability (performance drops from Train to OOT)
- Key drivers include credit behavior, customer tenure, and economic activity
- Ticket size has increased steadily since December 2020

---

## ⚙️ Methodology

- Data cleaning and missing value treatment
- Outlier handling using log transformations
- Temporal analysis of default rate
- Feature selection (correlation + Cramer's V)
- Modeling:
  - Logistic Regression
  - Random Forest

---

## 📉 Results

- Logistic Regression: Gini ~0.59 (Train) → ~0.37 (OOT)
- Random Forest: Gini ~0.66 (Train) → ~0.39 (OOT)

Results highlight overfitting and sensitivity to temporal shifts.

---

## 🔥 Next Steps

- Improve target definition (default classification)
- Incorporate more historical data (pre/post 2020)
- Add temporal features to capture behavior dynamics
- Explore customer segmentation using clustering techniques to identify behavioral patterns and generate new features (e.g., cluster-based risk profiles)

---

## 📌 Author

Samuel Robles
