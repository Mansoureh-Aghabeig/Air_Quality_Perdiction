# 🏭 Air Quality Prediction

This project explores and predicts air pollution trends in India using historical air quality data from the Indian Ministry of Environment and Pollution Control Board. Given India's high exposure to air pollution and its impact on public health, this work aims to analyze trends and build models for forecasting key pollutants.

## 📦 Dataset Overview

The dataset combines several years of records across Indian states and cities, tracking pollutants such as:

- RSPM (Respirable Suspended Particulate Matter)
- SO₂ (Sulphur Dioxide)
- NO₂ (Nitrogen Dioxide)

### 🔍 Key Questions Explored

- How has air quality changed over time in major Indian cities?
- Which states or cities show the highest average pollution levels?
- Are there seasonal trends in pollution?
- Can we relate pollution reduction to specific policy changes?
- How accurately can we predict RSPM levels using machine learning models?

---

## 📈 Suggested Visualizations

- 📉 **Line Plot**: Trend of average RSPM levels over the years.
- 🌡 **Heatmap**: Monthly pollutant levels across states.
- 🏙 **Bar Chart**: Top 10 most polluted cities.
- 📦 **Boxplot**: Seasonal distribution of RSPM levels.
- 🔄 **Trend Comparison**: Before vs. after major policy implementation.

Tools used: `matplotlib`, `seaborn`, `plotly`

---

## 🧠 Machine Learning Approach

We applied several regression models to predict RSPM levels:

- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**

### ✅ Evaluation Metrics

- **Mean Absolute Error (MAE)**: Average magnitude of errors (lower is better).
- **Mean Squared Error (MSE)**: Penalizes larger errors more.
- **R² Score**: Measures the proportion of variance explained by the model.



