# 📊 Big Data & Machine Learning Project

## Overview

A comprehensive Big Data and Machine Learning coursework project covering foundational to advanced data science techniques. The project uses real-world datasets including the NCI SEER Cancer dataset to implement and compare multiple ML algorithms, data manipulation with Pandas, large-scale data processing with PySpark, and multi-dimensional data visualization.

## Tech Stack

- **Language:** Python 3
- **Data Processing:** Pandas, NumPy, PySpark
- **Machine Learning:** Scikit-learn (Linear Regression, KNN, Decision Tree, Random Forest)
- **Visualization:** Matplotlib, Seaborn (2D and 3D plots)
- **Big Data:** Apache Spark (PySpark DataFrames)
- **Environment:** Jupyter Notebook
- **Dataset:** NCI SEER Cancer Registry (CRC_SEER_Modified.csv, NCI_SEER_CRC.csv)

## Features

- 📋 **Pandas DataFrames** — Data ingestion, cleaning, manipulation, and aggregation with Pandas
- 📈 **Data Visualization** — 2D and 3D data visualization using Matplotlib and Seaborn
- 📐 **Linear & Combined Regression** — Assignments 4 & 5: Linear regression modeling and feature analysis
- 🤖 **K-Nearest Neighbor (KNN)** — Classification using KNN algorithm on medical datasets
- ⚡ **PySpark Integration** — Large-scale data processing using Apache Spark DataFrames
- 🔬 **Cancer Prediction** — Final project: ML classification on NCI SEER colorectal cancer dataset

## How to Run

```bash
# Clone the repository
git clone https://github.com/Phoenixking-04/BIG-Data-project.git
cd BIG-Data-project

# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn pyspark jupyter

# Launch Jupyter Notebook
jupyter notebook

# Open any Assignment notebook (.ipynb) to run
# e.g., Assignment 2_Pandas DataFrames.ipynb
```

For PySpark assignments, ensure Java is installed:
```bash
# Install Java (required for PySpark)
java -version # Should be Java 8 or higher

# Then run PySpark notebooks normally via Jupyter
```

## Results / Outcomes

- ✅ Gradient Boosting achieved best accuracy at 69.9%
  on 30,001-record NCI SEER cancer dataset
- ✅ KNN (k=9) optimal configuration at 66.1% accuracy
- ✅ Feature importance reveals survival months (42.5%)
  and age (32.9%) as top predictors
- ✅ SHAP analysis confirms interpretable model decisions
  for healthcare disparity research
- ✅ PySpark pipeline successfully processes
  large-scale distributed datasets

## 🏆 Actual Model Results (NCI SEER Dataset — 30,001 Records)
| Model | Accuracy | Notes |
|-------|----------|-------|
| **Gradient Boosting** | **69.9%** | Best performer |
| Logistic Regression | 69.7% | Strong baseline |
| Decision Tree (depth=5) | 69.6% | Interpretable |
| KNN (k=9) | 66.1% | Best k value |
| KNN (k=7) | 65.8% | |
| Random Forest | 65.0% | Ensemble method |
| KNN (k=3) | 62.8% | Lower k overfits |

## 🔍 Feature Importance (Random Forest)
| Feature | Importance |
|---------|-----------|
| Survival Months | 42.5% |
| Age | 32.9% |
| Year of Diagnosis | 15.9% |
| Marital Status | 4.4% |
| Race | 2.4% |

## Key Findings
- Gradient Boosting outperforms all models at 69.9%
- Survival months and age are the strongest predictors
  (75.4% combined importance)
- Healthcare disparity analysis shows demographic
  patterns in survival rates
- SHAP analysis provides interpretable feature
  contributions for medical decision support

🔗 Developer: Kalyankumar Sandireddy | [LinkedIn](https://www.linkedin.com/in/kalyankumar-sandireddy-400681176)
