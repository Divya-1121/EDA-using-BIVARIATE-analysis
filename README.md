# 📊 Exploratory Data Analysis using Bivariate Analysis

> A beginner-friendly Python notebook demonstrating bivariate analysis techniques across four real-world datasets — visualizing relationships between pairs of variables using Seaborn, Pandas, and Matplotlib.

![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat-square&logo=jupyter)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12+-teal?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## 📌 Overview

Bivariate analysis examines the relationship between **two variables** at a time. This project walks through the most important visualization techniques used in real-world EDA, applied to four popular datasets.

**Datasets used:**

| Dataset | Description |
|---|---|
| 🍽️ Restaurant | Customer dining data — ratings, spend, restaurant type |
| 🚢 Titanic | Passenger survival data with categorical and numerical features |
| ✈️ Flights | Monthly passenger counts over multiple years |
| 🌸 Iris | Classic flower classification dataset with continuous features |

---

## 📊 Visualizations Covered

### 1. Scatter Plot — Numerical vs Numerical
Explores relationships between two continuous variables.  
**Example:** `rate (out of 5)` vs `num of ratings`, colored by `restaurant type`

### 2. Bar Plot — Categorical vs Numerical
Compares average or aggregated numerical values across categories.

### 3. Box Plot — Distribution & Outliers
Visualizes the spread, median, IQR, and outliers of a variable across categories.

### 4. Heatmap — Correlation Matrix
Displays pairwise correlations between all numerical features in a color-coded grid.

### 5. Pair Plot — All Pairwise Relationships
Shows scatter plots for every variable combination alongside distributions on the diagonal.

### 6. Line Plot — Trends Over Time
Reveals trends in sequential or time-indexed data.  
**Example:** Monthly passenger trends in the Flights dataset

---

## 🛠️ Tech Stack

| Library | Purpose |
|---|---|
| `pandas` | Data loading, cleaning, and wrangling |
| `seaborn` | Statistical data visualization |
| `matplotlib` | Plot customization and layout control |
| `numpy` | Numerical operations |
| `Google collab` | Interactive notebook environment |

---

## 📁 Project Structure

```
EDA-Using-Bivariate/
│
├── EDA USING BIVARIATE.ipynb   # Main analysis notebook
└── README.md                   # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8+ installed, then install the required libraries:

```bash
pip install pandas seaborn matplotlib numpy
```

### Clone the Repository

```bash
git clone https://github.com/your-username/EDA-Using-Bivariate.git
cd EDA-Using-Bivariate
```

### Run the Notebook

```bash
jupyter notebook "EDA USING BIVARIATE.ipynb"
```

---

## 🎯 Learning Outcomes

By working through this notebook, you will:

- Understand when and why to use bivariate analysis techniques
- Learn the Seaborn API for creating statistical visualizations
- Identify trends, patterns, and outliers across different dataset types
- Interpret correlation heatmaps and pairplots confidently
- Analyze relationships between categorical and numerical features
- Build a foundation for more advanced multivariate EDA

---

## ⚠️ Disclaimer

This project is created for **educational and learning purposes only**.  
All datasets used belong to their respective owners.

---

## 🙌 Acknowledgements

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/stable/index.html)
- [Kaggle Datasets](https://www.kaggle.com/datasets)

---

## 📅 Created

**2026** · MIT License

