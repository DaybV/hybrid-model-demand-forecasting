#  Weekly Demand Forecasting with Hybrid Model (Linear Regression + XGBoost)

This project aims to build a **hybrid machine learning model** to predict the weekly demand of meals across **77 logistics centers** and **51 different products**, within a highly seasonal and noisy environment.

##  Objective

Develop a robust model capable of accurately forecasting weekly demand by combining:

1. **A deterministic trend model** (Linear Regression).
2. **A machine learning model** (XGBoost Regressor) trained on the residuals to capture non-linear interactions and complex effects.

---

##  Methodology

### 1. Trend Modeling (Stage 1)
- Used **Linear Regression** to fit the general trend of each product-center combination.
- This model captures seasonal and global behavior using time as the main feature.
  

### 2.  Residual Modeling with XGBoost (Stage 2)
- Trained an **XGBoost Regressor** on the residuals from Stage 1.
- Features used include:
  - Lag feature
  - Rolling statistics (median,  min, max)
  - Prices, discounts, promotions
  - Day, month, year, season
  - Product sensitivity to discounts and promotions

---

## Performance

- **R² Score (Test Set): 0.81**
- **Explained Variance:** High accuracy in identifying general trends and peaks in demand.

---

##  Highlights

- **Hybrid approach**: Leverages strengths of deterministic + ML methods.
- **Temporal validation**: Uses rolling windows to validate performance over time.
- **Real-world complexity**: Models behave well under realistic demand variability.

---

##  Files

- `Model_Hybrid_final.ipynb`: Main notebook with data processing, modeling, and evaluation.
- `README.md`: Project description and overview (this file).
The kaggle dataset can be found at the following link [Food_Demand_Forecasting](https://www.kaggle.com/datasets/kannanaikkal/food-demand-forecasting/data)

---

## 👩‍💻 Author

**Dayana B.**  
Industrial Engineer specialized in Data Science & AI  
Visual Analytics | BI | Python | Machine Learning |
[LinkedIn](https://www.linkedin.com/in/dayanabedoyavalestt)

---

