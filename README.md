# 🌸 Iris Dataset - Exploratory Data Analysis (EDA)

A complete exploratory data analysis (EDA) project on the classic **Iris dataset**.  
This notebook explores the dataset through statistical summaries, visualizations, outlier detection, and feature correlation analysis to understand the structure and insights of the data before modeling.

---

## 📊 Dataset Overview

- **Source:** Built-in dataset from `sklearn.datasets`
- **Samples:** 150
- **Classes:** 3 species of Iris flowers
  - Setosa
  - Versicolor
  - Virginica
- **Features:**
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)

---

## ✅ Key EDA Steps

1. **Statistical Summary**
   - Mean, median, standard deviation, min/max
2. **Missing Values Check**
   - No missing values in the dataset
3. **Outlier Detection**
   - Boxplots and IQR method used
   - Few mild outliers in sepal width
4. **Correlation Analysis**
   - Strong positive correlation between petal length and petal width
   - Weak correlation between sepal width and other features
5. **Feature Distributions**
   - Histograms and KDE plots
   - Setosa is linearly separable; Versicolor and Virginica overlap
6. **Pair Plot**
   - Clear separation of Setosa class in petal-based features

---

## 📈 Visualizations Included

- Heatmap of correlations
- Boxplots for outlier detection
- Pair plots for multi-feature comparison
- Violin plots for class-wise feature distributions
- Histograms for individual features

---

## 📁 Files in this Repository

| File Name              | Description                           |
|------------------------|----------------------------------------|
| `iris_eda.ipynb`       | Main Jupyter/Colab notebook with EDA   |
| `README.md`            | Project overview and documentation     |

---

## 📦 Requirements

Install with `pip install -r requirements.txt` or use Google Colab (recommended).

