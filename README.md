
# 🤖 Supervised Machine Learning

This repository contains supervised learning models applied to various regression and classification problems using real-world datasets. The implementations are based on Python and popular libraries like `scikit-learn`, `statsmodels`, and `seaborn`. The models include linear regression, logistic regression, multilevel modeling, and count data models. Each script demonstrates practical steps in data preprocessing, feature engineering, model training, evaluation, and result interpretation.

---

## 📁 Project Structure

### 1. Simple and Multiple Linear Regression
- **Scripts**: `01 - SCRIPT - REGRESSÃO SIMPLES E MÚLTIPLA.py`, `Preço Casas.py`
- **Description**: Applies simple and multiple linear regression to predict house prices based on features like number of bedrooms, bathrooms, and area.
- **Key Techniques**:
  - Model training with OLS
  - Evaluation with R², RMSE
  - Residual analysis and visualization

### 2. Logistic Regression (Binary and Multinomial)
- **Script**: `02 - SCRIPT - MODELOS LOGÍSTICOS BINÁRIOS E MULTINOMIAIS.py`
- **Description**: Implements logistic regression models to predict categorical outcomes such as buying behavior or product preferences.
- **Key Techniques**:
  - Model building with `statsmodels`
  - Stepwise variable selection
  - Evaluation via ROC curve and confusion matrix

### 3. Count Data Regression
- **Script**: `03 - SCRIPT - MODELOS PARA DADOS DE CONTAGEM.py`
- **Description**: Analyzes count-type dependent variables using Poisson, Negative Binomial, ZIP, and ZINB models.
- **Key Techniques**:
  - Overdispersion diagnostics
  - Vuong test for model comparison
  - Interpretation of count model coefficients

### 4. Multilevel (Hierarchical) Modeling
- **Script**: `04 - SCRIPT - MODELAGEM MULTINÍVEL.py`
- **Description**: Explores multilevel regression models to handle data with hierarchical structure (e.g., students nested in schools).
- **Key Techniques**:
  - Varying intercept and slope models
  - Group-level variance interpretation
  - ICC (Intra-class Correlation Coefficient) analysis

### 5. HR Attrition Prediction (Binary Classification)
- **Script**: `Recursos Humanos.py`
- **Description**: Predicts employee attrition using binary logistic regression. Dataset includes features such as satisfaction, salary, and years at company.
- **Key Techniques**:
  - Dummy variable encoding
  - ROC/AUC and GINI evaluation
  - Customized confusion matrix with varying thresholds

---

## 🧰 Libraries Used
```python
pandas
numpy
matplotlib
seaborn
scikit-learn
statsmodels
pingouin
scipy
statstests
```

---

## 📊 Key Topics Covered
- Regression Analysis
- Classification Models
- Model Diagnostics and Metrics
- Feature Engineering
- Stepwise Selection
- Multilevel and Count Data Modeling

---
