# Crop Yield Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project is an end-to-end **Exploratory Data Analysis (EDA)** of crop yield data using Python. It focuses on understanding the dataset, cleaning and preparing the data, analyzing patterns and relationships, and generating meaningful insights related to crop yield.

## 🎯 Objectives
- Understand the structure and characteristics of the crop yield dataset.
- Clean and prepare the data for analysis.
- Handle missing values and duplicate records.
- Identify and analyze outliers.
- Perform univariate, bivariate, and multivariate analysis.
- Study relationships between yield and agricultural factors.
- Create meaningful visualizations and pivot tables.
- Extract useful insights from the data.

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📊 Dataset
The dataset contains agricultural information related to:
- Crop
- Crop Year
- Season
- State
- Area
- Production
- Annual Rainfall
- Fertilizer
- Pesticide
- Yield

The main focus of the analysis is **Yield** and its relationship with other crop and agricultural variables.

## 🔍 Project Workflow

### 1. Data Loading
The dataset is loaded using Pandas and initially inspected using functions such as `head()`, `tail()`, `shape`, `columns`, `info()`, and `describe()`.

### 2. Data Cleaning & Preparation
The notebook performs:
- Column-name standardization
- Text/categorical data cleaning
- Missing-value analysis and treatment
- Duplicate detection and removal
- Numerical data analysis
- Outlier detection
- Log transformation of yield where useful for analysis

### 3. Exploratory Data Analysis

**Univariate Analysis**
- Distribution of individual variables
- Crop, season, and state analysis
- Yield distribution
- Outlier analysis

**Bivariate Analysis**
- Yield vs Area
- Yield vs Production
- Yield vs Rainfall
- Yield vs Fertilizer
- Yield vs Pesticide
- Yield comparison across crops, seasons, and states

**Multivariate Analysis**
- Correlation analysis
- Heatmaps
- Relationships involving multiple agricultural variables

### 4. Visualizations
The project uses appropriate charts including:
- Bar charts
- Count plots
- Histograms
- Box plots
- Scatter plots
- Heatmaps

Each visualization is used to understand a particular question or relationship in the dataset.

### 5. Pivot Tables
Pivot tables are used to summarize and compare crop yield, production, and other agricultural information across different categories.

## 💡 Key Outcomes
The analysis helps identify:
- How crop yield varies across crops, seasons, and states.
- Relationships between yield and agricultural factors.
- Distribution and variation in the dataset.
- Correlations between numerical variables.
- Data-quality issues such as missing values, duplicates, and outliers.

## 📁 Project Structure

```text
Crop-Yield-EDA/
│
├── Crop Yield Analysis project.ipynb
├── README.md
└── dataset/
    └── unclean_crop_yield.csv
```

## ▶️ How to Run

1. Download or clone this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Start Jupyter Notebook:

```bash
jupyter notebook
```

4. Open `Crop Yield Analysis project.ipynb`.
5. Run the notebook cells from top to bottom.

## 🎓 Skills Demonstrated
**Python | Pandas | NumPy | Data Cleaning | EDA | Data Visualization | Statistical Analysis | Correlation Analysis | Pivot Tables | Insight Generation**

## 👤 Author
**Piyush Nehete**

---
⭐ If you find this project useful, consider giving the repository a star!
