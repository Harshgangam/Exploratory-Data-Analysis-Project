# 📊 Exploratory Data Analysis of 1000 Sales Records Using Python

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of a sales transaction dataset containing 1,000 records and 14 columns. It applies data preparation, statistical analysis, data visualization, correlation analysis, time series analysis, clustering, dimensionality reduction, and model evaluation using Python.

The project was developed as part of the **BCSE331L – Exploratory Data Analysis** course at Vellore Institute of Technology (VIT).

The primary objective is to understand sales and profitability patterns, identify relationships between variables, detect potential outliers, analyze sales trends, and apply data mining and machine learning techniques to the dataset.

## 👨‍🎓 Student Details

- **Name:** Gangam Harsh
- **Registration Number:** 23BDS0214
- **Institution:** Vellore Institute of Technology (VIT)
- **Course:** BCSE331L – Exploratory Data Analysis
- **Project Title:** Exploratory Data Analysis of 1000 Sales Records Using Python

## 🎯 Problem Statement

The objective of this project is to perform comprehensive exploratory data analysis on a real-world-style sales transaction dataset using Python.

The analysis focuses on preparing and transforming the data, summarizing statistical characteristics, visualizing distributions and relationships, examining time-dependent patterns, applying clustering and dimensionality reduction techniques, and evaluating predictive models.

The project follows the major topics covered in the Exploratory Data Analysis course syllabus.

## 📂 Dataset Description

### Dataset Name
**1000 Sales Records**

### Dataset Source
The dataset is available at the following link:

[Download / Access the 1000 Sales Records Dataset](https://raw.githubusercontent.com/salemprakash/EDA/main/Data/1000%20Sales%20Records.csv)

### Dataset Overview

The dataset contains 1,000 sales transactions from a fictional global business, with information about orders, products, geographical regions, sales channels, revenue, costs, and profits.

| Attribute | Description |
|---|---|
| Number of records | 1,000 |
| Number of columns | 14 |
| Data types | Numerical, categorical, date, and identifier |
| Time period | January 2010 – July 2017 |
| Domain | Sales and business analytics |

### Important Variables

The dataset includes the following attributes:

- **Region:** Geographical sales region.
- **Country:** Country where the transaction occurred.
- **Item Type:** Category of the product sold.
- **Sales Channel:** Online or offline sales channel.
- **Order Priority:** Priority assigned to an order.
- **Order Date:** Date the order was placed.
- **Order ID:** Unique order identifier.
- **Ship Date:** Date the order was shipped.
- **Units Sold:** Number of units sold.
- **Unit Price:** Selling price per unit.
- **Unit Cost:** Cost per unit.
- **Total Revenue:** Total revenue generated.
- **Total Cost:** Total cost associated with the transaction.
- **Total Profit:** Profit generated from the transaction.

## 🛠️ Technologies and Libraries Used

The project uses Python and its data analysis, statistical computing, visualization, and machine learning libraries.

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Jupyter Notebook | Interactive development and documentation |
| Pandas | Data loading, cleaning, transformation, and analysis |
| NumPy | Numerical computing and array operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical data visualization |
| SciPy | Statistical analysis and hypothesis testing |
| Scikit-learn | Machine learning, clustering, dimensionality reduction, and evaluation |

### Official Documentation

- [Python](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [SciPy Documentation](https://docs.scipy.org/doc/scipy/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)

## 📚 Project Modules and Methodology

The notebook is organized into the following major modules.

### Module 1: Introduction to Exploratory Data Analysis

This module introduces EDA concepts and examines the structure and characteristics of the sales dataset.

**Topics covered:**
- Introduction and objectives of EDA.
- Data types and measurement scales.
- EDA versus classical and Bayesian analysis.
- Importing Python libraries.
- Loading and inspecting the dataset.
- Understanding data dimensions, columns, and data types.
- Data dictionary and initial data-quality checks.

### Module 2: Data Transformation

This module demonstrates techniques for preparing and transforming data for analysis.

**Topics covered:**
- Checking and removing duplicate records.
- Replacing coded values with meaningful labels.
- Converting columns to appropriate data types.
- Discretization and binning.
- Handling missing data.
- Mean, median, and mode imputation.
- Row deletion and information loss.
- Maximum Likelihood Estimation (MLE).

Missing-data handling is demonstrated using an artificially modified copy of the dataset because the original dataset contains no missing values.

### Module 3: Correlation Analysis and Time Series Analysis

This module investigates relationships between sales variables and examines how revenue changes over time.

**Topics covered:**
- Correlation analysis.
- Relationships between numerical variables.
- Statistical interpretation of correlations.
- Time series analysis.
- Monthly and yearly sales and revenue patterns.
- Trend and seasonality analysis.
- Autocorrelation analysis.

### Module 4: Data Summarization and Visualization

This module uses descriptive statistics and visualizations to understand the distribution of sales and profitability.

**Topics covered:**
- Statistical summary measures.
- Measures of central tendency and dispersion.
- Distribution analysis.
- Skewness and kurtosis.
- Outlier identification using statistical methods.
- Contingency tables and cross-tabulation.
- Categorical data analysis.
- Graphical representation and interpretation of findings.

### Module 5: Clustering Algorithms

This module explores clustering techniques for identifying groups and potential anomalies in the data.

**Algorithms and techniques covered:**
- Spectral clustering.
- Document clustering using a synthetic text demonstration.
- Minimum Spanning Tree (MST) clustering.
- Model-based clustering.
- Expectation-Maximization (EM) algorithm.
- Gaussian Mixture Models (GMM).
- Hierarchical agglomerative clustering.
- Outlier detection using clustering.
- Cluster evaluation using silhouette scores and other relevant measures.

### Module 6: Dimensionality Reduction

This module explores techniques for reducing the number of dimensions while retaining important information.

**Techniques covered:**
- Principal Component Analysis (PCA).
- Singular Value Decomposition (SVD).
- Factor Analysis.
- Intrinsic dimensionality estimation.
- Multidimensional Scaling (MDS).
- Manifold learning using Isomap.
- Self-Organizing Maps (SOM).

### Module 7: Model Development and Evaluation

This module demonstrates predictive modelling and model evaluation techniques.

**Topics covered:**
- Regression modelling.
- Predicting Total Profit.
- Model performance evaluation.
- Root Mean Squared Error (RMSE).
- Mean Absolute Error (MAE).
- Coefficient of determination (R²).
- Confusion matrix.
- Classification accuracy demonstration using synthetic data.
- Introduction to reinforcement learning.

The regression analysis uses the sales dataset, while the classification accuracy and reinforcement-learning examples are synthetic demonstrations.

## 📈 Key Findings and Results

The following findings are documented in the notebook.

### 1. Data Quality
- The dataset contains 1,000 records and 14 columns.
- No missing values or duplicate rows were found in the original dataset.
- Missing-data handling techniques were demonstrated using artificially introduced missing values.

### 2. Statistical Analysis
- Units Sold has approximately symmetric and relatively flat distribution characteristics.
- Total Profit is right-skewed, with the mean exceeding the median.
- Statistical outlier detection identified potentially unusual high-profit transactions.

### 3. Correlation Analysis
- Units Sold and Unit Price show little to no linear correlation.
- Total Profit has moderate positive correlations with Units Sold and Unit Price.
- Unit Price and Unit Cost are strongly correlated.
- Region and Sales Channel did not show a statistically significant association in the reported chi-square analysis.

### 4. Sales and Time Series Analysis
- Cosmetics, Household, and Office Supplies contribute substantially to total profit.
- Yearly revenue varies across the observed period.
- The 2017 data covers only part of the year.
- Monthly revenue analysis did not identify a strong trend, seasonality, or autocorrelation.

### 5. Clustering and Outlier Detection
- Clustering methods were used to explore potential group structures and unusual observations.
- Some methods identified potential anomalies that require further investigation.
- The relatively low silhouette scores suggest that the cluster structure is limited or overlapping.

### 6. Dimensionality Reduction
- The first two principal components explain approximately 93.3% of the variance.
- The first three principal components explain approximately 97.3% of the variance.
- SVD reproduces the PCA results for the corresponding analysis.
- Intrinsic dimensionality estimates vary according to the method used.

### 7. Regression Model Evaluation

The notebook reports the following results for the regression model predicting Total Profit without using Total Revenue or Total Cost as predictors.

| Evaluation Metric | Reported Result |
|---|---:|
| R² Score | 0.796 |
| RMSE | 162,083 |
| MAE | 111,502 |

These metrics describe the model's performance on the test data used in the notebook.

## 💡 Conclusion

This project demonstrates how exploratory data analysis can be used to understand sales data, evaluate data quality, identify statistical patterns, visualize relationships, investigate potential outliers, and apply machine learning techniques.

The analysis suggests that profitability is associated with sales quantity and product-specific price and cost characteristics. Regional and sales-channel differences are comparatively limited in the analyses performed.

Clustering and dimensionality reduction provide additional perspectives on the dataset, while regression modelling demonstrates how sales attributes can be used to predict profit.

Overall, the project provides practical experience with Python-based data analysis, statistical reasoning, visualization, clustering, dimensionality reduction, and model evaluation.

## ⚠️ Limitations

- The dataset represents fictional business transactions and may not reflect every characteristic of real-world sales.
- The analysis is observational and does not establish causal relationships.
- The dataset covers an incomplete year in 2017.
- Some financial variables are mathematically derived from other columns.
- Price and cost are closely associated with item type.
- Some computationally expensive analyses use a subset of the data.
- The document-clustering, classification-accuracy, and reinforcement-learning demonstrations do not directly represent predictive results from the sales dataset.
- Potential outliers identified by statistical and clustering methods require further investigation before being considered errors.

## 🚀 How to Run the Project

### Prerequisites

Install Python and Jupyter Notebook, or use Visual Studio Code with the Jupyter extension.

### Step 1: Clone the repository

Open a terminal and run:

```bash
git clone https://github.com/Harshgangam/Exploratory-Data-Analysis-Project.git
```

### Step 2: Navigate to the project directory

```bash
cd Exploratory-Data-Analysis-Project
```

### Step 3: Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
```

### Step 4: Open the notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Alternatively, open the repository folder in Visual Studio Code and select the notebook:

`23BDS0214_EDA_Project.ipynb`

### Step 5: Execute the notebook

Run the notebook cells sequentially, from top to bottom.

The notebook attempts to load the dataset directly from its source URL. If the URL is unavailable, follow the notebook's manual-upload fallback instructions.

## 📁 Repository Structure

```text
Exploratory-Data-Analysis-Project/
│
├── 23BDS0214_EDA_Project.ipynb
└── README.md
```

The repository contains the Jupyter Notebook and this README file. The dataset is accessed from the external source linked above.

## 🔗 Project Links

- **GitHub Repository:** [Exploratory-Data-Analysis-Project](https://github.com/Harshgangam/Exploratory-Data-Analysis-Project)
- **Jupyter Notebook:** [23BDS0214_EDA_Project.ipynb](https://github.com/Harshgangam/Exploratory-Data-Analysis-Project/blob/main/23BDS0214_EDA_Project.ipynb)
- **Dataset:** [1000 Sales Records CSV](https://raw.githubusercontent.com/salemprakash/EDA/main/Data/1000%20Sales%20Records.csv)
- **Python:** [Official Website](https://www.python.org/)
- **Jupyter:** [Official Website](https://jupyter.org/)
- **Pandas:** [Official Documentation](https://pandas.pydata.org/docs/)
- **NumPy:** [Official Documentation](https://numpy.org/doc/)
- **Matplotlib:** [Official Documentation](https://matplotlib.org/stable/)
- **Seaborn:** [Official Documentation](https://seaborn.pydata.org/)
- **SciPy:** [Official Documentation](https://docs.scipy.org/doc/scipy/)
- **Scikit-learn:** [Official Documentation](https://scikit-learn.org/stable/)

## 👤 Author

**Gangam Harsh**  
B.Tech – Computer Science and Engineering (Data Science)  
Vellore Institute of Technology (VIT)

GitHub: [@Harshgangam](https://github.com/Harshgangam)

---

⭐ If you find this project useful, feel free to explore the notebook and its analysis.
