# Wine Quality Prediction - Comprehensive Data Analysis

A comprehensive data science project that analyzes physicochemical properties of wine samples to predict quality using machine learning and statistical analysis.

## 📋 Overview

This project aims to understand how various physicochemical properties influence wine quality and build a predictive model using data-driven approaches. Wine producers can use measurable chemical attributes to objectively assess quality, moving beyond subjective human evaluation.

## 🎯 Objectives

- Identify which features most strongly influence wine quality
- Understand relationships between chemical properties and taste perception  
- Build predictive models to reliably estimate wine quality (0-10 scale)
- Provide actionable insights for wine quality control

## 📊 Dataset

**File:** `dataproject.csv`

- **Samples:** 1,145 wine records
- **Features:** 12 physicochemical properties
- **Target:** Wine quality rating (0-10 scale)

### Features

| Feature | Description |
|---------|-------------|
| **Fixed Acidity** | Non-volatile acids (tartaric acid) - contributes to sour taste |
| **Volatile Acidity** | Evaporating acids (acetic acid) - vinegar-like smell if high |
| **Citric Acid** | Weak organic acid - adds freshness and flavor |
| **Residual Sugar** | Sugar after fermentation (g/L) - affects sweetness |
| **Chlorides** | Salt content - excess negatively impacts quality |
| **Free Sulfur Dioxide** | SO₂ available for preservation and oxidation control |
| **Total Sulfur Dioxide** | Total bound + free SO₂ - aids wine preservation |
| **Density** | Mass per unit volume - influenced by sugar and alcohol |
| **pH** | Acidity/alkalinity measure - lower pH = more acidic |
| **Sulphates** | Wine additive for preservation |
| **Alcohol** | Alcohol percentage by volume |

## 📁 Project Structure

```
.
├── PROJECT.ipynb          # Main Jupyter notebook with full analysis
├── dataproject.csv        # Wine quality dataset
├── README.md              # This file
└── .gitattributes         # Git configuration for consistent line endings
```

## 📖 Notebook Contents

The analysis notebook is organized into 8 comprehensive sections:

0. **Introduction & Problem Context** - Problem statement and objectives
1. **Data Overview & Loading** - Dataset structure and basic statistics
2. **Data Cleaning & Preparation** - Handling missing values and data quality
3. **Exploratory Data Analysis (EDA)** - Visualizations and distributions
4. **Detailed Feature-Level Analysis** - Individual feature relationships with quality
5. **Statistical Analysis for Modeling** - Correlation and hypothesis testing
6. **Data Preprocessing for Machine Learning** - Scaling and transformation
7. **Feature Selection for Machine Learning** - Identifying most important features
8. **Key Findings & Recommendations** - Summary and actionable insights

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Jupyter Notebook
- pandas, numpy, scikit-learn, matplotlib, seaborn

### Installation

```bash
# Install required packages
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# Navigate to project directory
cd "ds ko project 71"

# Launch Jupyter
jupyter notebook PROJECT.ipynb
```

## 📊 Key Analysis Areas

- **Descriptive Statistics** - Understanding feature distributions and wine quality spread
- **Correlation Analysis** - Identifying feature relationships with quality  
- **Feature Engineering** - Creating new features for improved predictions
- **Data Visualization** - Distribution plots, heatmaps, and scatter plots
- **Statistical Testing** - Hypothesis testing for significant relationships
- **Model Preparation** - Feature scaling and normalization for ML algorithms

## 🔍 Expected Insights

- Which physicochemical features are strongest quality predictors
- How acidity (fixed/volatile/citric) affects wine perception
- The influence of alcohol content and residual sugar on quality
- Optimal ranges for key parameters to maximize wine quality

## 📝 Notes

- All line endings are configured to use LF for cross-platform consistency (`.gitattributes`)
- The dataset is ready for machine learning model development
- EDA provides foundation for feature selection and model building

## 📚 Resources

- Dataset based on wine quality studies
- Analysis covers data exploration through model preparation stages
- Suitable for regression modeling, classification, or clustering tasks

---

**Created:** March 2026  
**Project Type:** Machine Learning / Data Science  
**Status:** Active Development
