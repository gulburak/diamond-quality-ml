# Diamond Price & Quality Analysis — Data-Driven Decision Making

## Overview
This project applies data science and machine learning to a **business decision-making problem**: selecting the best diamond options based on the trade-off between price and quality.

The task was approached as a consulting-style case, combining exploratory analysis, predictive modeling, and actionable recommendations.

---

## Dataset
- Dataset size: 6,000 samples × 9 features
- Target variable: Diamond price

The dataset includes physical and quality-related attributes such as carat, cut, color, clarity, and dimensions.

---

## Approach
The project followed a structured data science workflow:
- Exploratory data analysis to understand feature relationships
- Data preprocessing and feature encoding
- Regression modeling to estimate diamond prices
- Evaluation of price–quality trade-offs
- Final recommendation of optimal diamond choices with clear justification

---

## Model
- **Algorithm:** Random Forest Regressor
- **Rationale:** Ability to capture non-linear relationships and interactions between diamond attributes
- **Evaluation Metric:** Regression metrics, including R²

---

## Results
- **R² score:** 0.985

The model accurately captures pricing patterns and enables reliable comparison between diamonds of similar quality.

---

## Key Outcome
Based on model predictions and analytical insights, several diamonds were identified as offering the **best value for money**, balancing quality attributes against price.

The final recommendation is supported by both quantitative analysis and domain reasoning.

---

## Tools & Libraries
Python, pandas, NumPy, scikit-learn, matplotlib

---

## Key Takeaways
- Machine learning can support data-driven product selection and pricing decisions
- Combining predictive models with domain understanding leads to actionable insights
- This project demonstrates the application of ML beyond prediction, toward decision support
