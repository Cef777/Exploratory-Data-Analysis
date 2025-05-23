# 🛳️ Titanic Dataset - Exploratory Data Analysis (EDA)

![Titanic](https://upload.wikimedia.org/wikipedia/commons/f/fd/RMS_Titanic_3.jpg)

## 📘 Overview

This project presents an **Exploratory Data Analysis (EDA)** of the well-known [Titanic dataset](https://www.kaggle.com/c/titanic/data). The primary goal is to explore factors that influenced passenger survival during the RMS Titanic disaster in 1912 using statistical and graphical EDA techniques.

---

## 📌 Objectives

- Apply EDA techniques to understand the structure and characteristics of the dataset.
- Investigate the relationship between passenger attributes (e.g., class, gender, age) and survival outcomes.
- Develop insights that can guide future predictive modeling tasks.

---

## 📂 Dataset Summary

| Attribute        | Description |
|------------------|-------------|
| `PassengerId`    | Unique ID for each passenger |
| `Survived`       | Survival (0 = No, 1 = Yes) |
| `Pclass`         | Passenger Class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| `Name`           | Name of the passenger |
| `Sex`            | Gender |
| `Age`            | Age in years |
| `SibSp`          | Siblings/Spouses aboard |
| `Parch`          | Parents/Children aboard |
| `Ticket`         | Ticket number |
| `Fare`           | Passenger fare |
| `Cabin`          | Cabin number |
| `Embarked`       | Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

> 🧮 Rows: 891 | Columns: 12

---

## 🧪 Tools & Libraries

- **Python 3**
- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`
- `Jupyter Notebook`

---

## 🔍 Analysis Workflow

1. **Data Import & Preview**
2. **Data Cleaning**
   - Missing value handling
   - Column renaming
   - Feature engineering (e.g., Deck from Cabin)
3. **Univariate Analysis**
4. **Bivariate & Multivariate Analysis**
5. **Insight Generation**

---

## 📊 Visualizations

### Survival Distribution
![Survival Barplot](images/survival_distribution.png)

### Class vs. Survival
![Class Survival](images/class_vs_survival.png)

### Gender Impact
![Gender Survival](images/gender_survival.png)

### Age Distribution (KDE)
![Age KDE](images/age_kde.png)

### Heatmap of Correlations
![Heatmap](images/correlation_heatmap.png)

> 📷 _Place your analysis visual outputs in a `/images` directory and update links above accordingly._

---

## 🧠 Key Insights

- **Passenger Class:** 1st Class passengers had the highest survival rates.
- **Gender:** Females had significantly higher survival odds than males.
- **Age:** Children under 16 had a better chance of survival, particularly in higher classes.
- **Fare:** Higher fares (typically paid by upper-class passengers) slightly correlated with survival.
- **Family:** No strong survival correlation found based on family traveling with passengers (SibSp/Parch).

---

## 📌 Conclusions

- Socioeconomic status played a significant role in survival.
- Gender and age were strong survival indicators, consistent with "women and children first."
- These insights can be foundational for predictive modeling.

---

## 💡 Recommendations for Future Work

- Investigate engineered features like `Deck` and `Title` (from `Name`).
- Explore non-linear models to capture complex interactions.
- Apply machine learning to test predictive performance.

