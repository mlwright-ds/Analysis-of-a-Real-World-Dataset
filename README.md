🍷 Wine Dataset Analysis (Python)
📌 Overview

This project performs exploratory data analysis (EDA) on a real-world dataset of wine samples to uncover patterns, relationships, and insights across different chemical properties.

The dataset is sourced from the scikit-learn library and is widely used for classification and statistical analysis.

📂 Dataset
Source: Built-in dataset from scikit-learn
Format: Loaded directly in Python or via CSV
Observations: 178 wine samples
Features: 13 chemical attributes + 1 target variable

🧾 Key Features
alcohol – Alcohol content
malic_acid – Malic acid concentration
ash – Ash content
alcalinity_of_ash – Mineral content measure
magnesium – Magnesium level
total_phenols – Phenolic compounds
flavanoids – Flavonoid concentration
color_intensity – Color richness
proline – Amino acid content
target – Wine class (0, 1, 2)

🎯 Objectives
Perform data cleaning and validation
Conduct exploratory data analysis (EDA)
Visualize relationships between features
Identify patterns across wine classes
Generate meaningful insights from real-world data

🧠 Project Workflow

🔹 1. Data Loading
Loaded dataset using:
from sklearn.datasets import load_wine
Converted into a Pandas DataFrame for analysis

🔹 2. Data Exploration
Checked:
Dataset shape
Data types
Missing values
Duplicate records
Generated summary statistics

🔹 3. Data Visualization
Used libraries like:
Pandas
Matplotlib
Seaborn

Visualizations include:

📊 Correlation heatmap
📈 Feature distributions (histograms)
🔍 Scatter plots (feature relationships)
📦 Boxplots (outlier detection)

🔹 4. Key Insights
Strong correlations exist between several chemical features
Certain variables (e.g., alcohol, color intensity) help distinguish wine classes
Dataset is clean with:
No missing values
No duplicate records
Some features show potential outliers

🔹 5. Real-World Impact

This type of analysis can be used for:

Wine classification and quality assessment
Feature selection for machine learning models
Understanding chemical profiles of products
Supporting data-driven decisions in food science

📊 Results
Successfully explored and visualized dataset
Identified relationships between variables
Produced clear, interpretable visual insights

🛠️ Technologies Used
Python
pandas
matplotlib
seaborn
scikit-learn

⚠️ Limitations
Dataset is relatively small (178 samples)
Limited to chemical properties only
No time-series or external factors included
