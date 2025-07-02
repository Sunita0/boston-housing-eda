# boston-housing-eda
Exploratory Data Analysis on the Boston Housing dataset
# boston-housing-eda
Exploratory Data Analysis on the Boston Housing dataset
# 🏡 Boston Housing EDA

This project performs detailed **Exploratory Data Analysis (EDA)** on the Boston Housing Dataset, which contains information about housing prices in Boston suburbs.
The goal is to understand key patterns, detect outliers, analyze feature relationships, and identify the most influential variables affecting housing prices.
---
## 📌 Dataset Overview
The dataset includes 506 observations and 14 features, such as:
- Crime rate (`CRIM`)
- Proportion of residential land zoned (`ZN`)
- Average number of rooms (`RM`)
- Pupil-teacher ratio (`PTRATIO`)
- Lower status population percentage (`LSTAT`)
- Median home value (`MEDV`) — *Target Variable*
---
## 🔍 EDA Highlights
- **Missing value handling**
- **Univariate analysis** using histograms and boxplots
- **Outlier detection** using Z-score
- **Skewness correction** using `log1p()` and `sqrt()`
- **Correlation heatmap** to find relationships
- **Scatter plots** for key features vs target
- **Feature selection** based on correlation

---

## 📊 Visualizations

Some key plots included:
- Histogram of features
- Boxplots to identify outliers
- Correlation heatmap
- Scatter plots: `RM` vs `MEDV`, `LSTAT` vs `MEDV`



---

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Files

| File              | Description                              |
|-------------------|------------------------------------------|
| `boston_eda.ipynb` | Full EDA code and analysis               |
| `data.csv`         | Dataset used (optional)                  |
| `boxplots.png`     | Outlier visualization (optional)         |
| `heatmap.png`      | Correlation matrix (optional)            |
![image](https://github.com/user-attachments/assets/51824f58-0d06-4f26-9ded-ece59700209b)
![heatmap](https://github.com/user-attachments/assets/0190b1c6-f21f-46a5-96cc-23991f06698f)
![scatter](https://github.com/user-attachments/assets/26a9a01c-cf78-4a7c-aefe-01239db0aafc)
