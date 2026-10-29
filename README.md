# Wine Quality Data Analysis
# Wine Quality Data Analysis

## Project Overview

This project focuses on Exploratory Data Analysis (EDA) and data preprocessing using the Wine Quality dataset.

The objective is to examine the physicochemical characteristics of wine samples, investigate data quality issues, identify potential outliers, and explore relationships between wine properties and quality ratings.

The analysis was conducted using Python and Jupyter Notebook as part of the **Big Data and Energy Data Analysis** course.

## Dataset Description

The Wine Quality dataset contains 1,599 observations and 12 variables:

- **11 input features:** Physicochemical properties of wine.
- **1 target variable:** Wine quality rating (`quality`).

The dataset is available from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality).

## Project Objectives

1. Load and examine the dataset.
2. Identify and handle missing values.
3. Perform descriptive statistical analysis.
4. Detect and treat potential outliers using the IQR method.
5. Visualize the distribution of wine quality ratings.
6. Investigate correlations among physicochemical features.
7. Explore pairwise relationships using a scatter plot matrix.

## Dataset
- The dataset that is given to you with this lab activity, is a Wine Quality dataset that can be downloaded as well from the UCI Machine Learning Repository at the following link: https://archive.ics.uci.edu/ml/datasets/wine+quality

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

```text
Wine Quality Data Analysis/
├── data/
│   └── winequality.csv
├── figure/
├── notebook/
│   └── Wine_Quality.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

The `figure/` directory is reserved for exported visualizations.

## Methodology

### 1. Data Loading and Examination
Imported the dataset using Pandas and examined its structure.

### 2. Data Preprocessing
Investigated missing values and applied mean imputation.

### 3. Descriptive Statistical Analysis
Examined summary statistics to understand the distributions and variability of numerical features.

### 4. Outlier Detection and Treatment
Used a boxplot and the Interquartile Range (IQR) method to investigate and filter potential outliers in `total sulfur dioxide`.

### 5. Exploratory Data Visualization
Generated a wine quality histogram, correlation heatmap, and scatter plot matrix.

## Key Findings

The analysis demonstrated how data preprocessing and exploratory visualizations can be used to investigate wine characteristics and their relationships with quality ratings.

- Missing-value analysis identified the need for data cleaning.
- Descriptive statistics supported the investigation of potential extreme observations.
- IQR-based filtering was applied to the `total sulfur dioxide` feature.
- The histogram provided an overview of wine quality ratings.
- The correlation heatmap and scatter plot matrix supported the examination of relationships between features.

## Limitations

- Mean imputation may influence data distributions and correlations.
- Mean imputation of missing target ratings may introduce non-discrete values.
- IQR-based filtering may remove valid extreme observations.
- Correlation does not establish causation.
- Predictive machine learning models were not evaluated.

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/damisar/Wine_Quality_Data_Analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Wine_Quality_Data_Analysis
   ```

3. Install the required dependencies:

   ```bash
   python -m pip install -r requirements.txt
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `notebook/Wine_Quality.ipynb` and run the cells in order.

## Future Improvements

- Compare alternative missing-value treatment techniques.
- Investigate outliers across additional variables.
- Perform further feature analysis.
- Develop and evaluate predictive machine learning models.

## Conclusion

This project demonstrates the role of exploratory data analysis and data preprocessing in understanding data characteristics, addressing data quality issues, and preparing datasets for further analysis.



