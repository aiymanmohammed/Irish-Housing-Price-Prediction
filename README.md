# Irish Housing Price Prediction

## Overview

This project analyses the Dublin residential property market using machine learning techniques to predict house prices (price per square foot) and classify buyer behaviour. The analysis covers the full data science pipeline — from exploratory data analysis and feature engineering through to model training, evaluation, and interpretation.

The project was completed as part of the **IS6052 Predictive Analytics** module at **University College Cork (UCC)**.

---

## Data Source

The dataset used is `Ireland_House_Price_Final.csv`, containing **13,320 property listings** across Dublin's four local authorities:

- Dublin City Council (DCC)
- Fingal
- Dún Laoghaire-Rathdown
- South Dublin

| Feature | Description |
|---|---|
| `property_scope` | Type of property (e.g., Constructed Space, Land Parcel) |
| `availability` | Availability status or move-in date |
| `location` | Dublin local authority area |
| `size` | Number of bedrooms |
| `total_sqft` | Total floor area in square feet |
| `bath` | Number of bathrooms |
| `balcony` | Number of balconies |
| `buying or not buying` | Purchase status |
| `BER` | Building Energy Rating (A–G) |
| `Renovation needed` | Whether renovation is required |
| `price-per-sqft-$` | Target variable — price per square foot in USD |

---

## Models Used

| Model | Purpose |
|---|---|
| **Linear Regression** | Baseline regression for price prediction |
| **Lasso Regression** | Regularised regression with feature selection |
| **Decision Tree** | Interpretable classification and regression |
| **Random Forest** | Ensemble model for robust price prediction |
| **Support Vector Machine (SVM/SVR)** | Non-linear regression and classification |
| **MLP (Neural Network)** | Deep learning baseline for regression |

Models were evaluated using **R²**, **RMSE**, and **MAE**. Cross-validation (KFold) and hyperparameter tuning (GridSearchCV, RandomizedSearchCV) were applied where appropriate.

---

## How to Run

**1. Clone the repository**
```bash
git clone https://github.com/aiymanmohammed/ireland-house-price-prediction.git
cd ireland-house-price-prediction
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Launch the notebook**
```bash
jupyter notebook Housing_PricesIndividualAssignment_AiymanMohammed.ipynb
```

> Make sure `Ireland_House_Price_Final.csv` is in the same directory as the notebook before running.

---

## Tech Stack

- **Language:** Python 3
- **Data Processing:** pandas, NumPy
- **Visualisation:** Matplotlib, Seaborn
- **Machine Learning:** scikit-learn
- **Dimensionality Reduction:** PCA
- **Environment:** Jupyter Notebook / Google Colab

---

## Author

**Aiyman Mohammed**  
MSc Business Analytics — University College Cork (UCC)  
[LinkedIn](https://www.linkedin.com/in/aiyman-mohammed-810225205) | [GitHub](https://github.com/aiymanmohammed)
