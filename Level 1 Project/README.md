# Level 1 Project: Data Cleaning & Exploratory Data Analysis

## Overview
This project focuses on fundamental data science skills including data cleaning, preprocessing, and exploratory data analysis (EDA). Students will learn how to handle real-world datasets and uncover meaningful patterns through visualization and statistical analysis.

## Project Objectives
- **Data Cleaning & Preprocessing**: Learn to handle missing values, data type conversions, and data quality issues
- **Data Exploration**: Understand dataset structure, distributions, and relationships between variables
- **Visualization**: Create meaningful visualizations to communicate insights
- **Statistical Analysis**: Perform descriptive statistics and basic correlations

## Tasks

### Task 1: Data Cleaning & Preprocessing
**File**: `Task1_data_cleaning_preprocessing.ipynb`

**Dataset**: Stock Price Dataset

**Key Activities**:
- Import and explore the dataset structure
- Handle missing values appropriately
- Convert data types (e.g., date columns)
- Clean and prepare data for analysis
- Document data quality issues and solutions

**Skills Covered**:
- Loading CSV files with pandas
- Data exploration with `.info()`, `.head()`, `.describe()`
- Missing value detection and handling
- Data type conversion

**Outcomes**:
- A clean, preprocessed dataset ready for analysis
- Understanding of data quality assessment techniques

---

### Task 2 & 3: Exploratory Data Analysis (EDA)
**File**: `task2&3_EDA.ipynb`

**Dataset**: Stock Price Dataset

**Key Activities**:
- Perform univariate analysis (distribution of individual variables)
- Perform bivariate analysis (relationships between variables)
- Create comprehensive visualizations
- Calculate summary statistics and correlations
- Identify trends and patterns

**Skills Covered**:
- Univariate analysis techniques
- Correlation analysis and heatmaps
- Matplotlib and Seaborn visualization
- Distribution analysis (histograms, box plots, KDE plots)
- Categorical data analysis

**Visualizations Created**:
- Distribution plots (histograms, KDE)
- Correlation heatmaps
- Box plots and violin plots
- Scatter plots for relationships
- Time series plots (if applicable)

---

## Dataset Information

**Stock Price Dataset**:
- Contains historical stock price data
- Columns: Date, Open, High, Low, Close, Volume
- Time series data spanning multiple periods
- Some missing values in OHLC columns

## Technologies & Tools

| Tool | Purpose |
|------|---------|
| **Python** | Programming language |
| **Pandas** | Data manipulation and cleaning |
| **NumPy** | Numerical computations |
| **Matplotlib** | Basic visualization |
| **Seaborn** | Statistical visualization |

## Key Learnings

Upon completing this project, you should understand:
1. How to assess and cleanse real-world data
2. Techniques for handling missing values and outliers
3. How to explore and visualize data effectively
4. Basic statistical measures and their interpretation
5. How to communicate findings through visualizations

## How to Run

1. Ensure all required libraries are installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

2. Navigate to the project directory

3. Run the notebooks in order:
   - `Task1_data_cleaning_preprocessing.ipynb`
   - `task2&3_EDA.ipynb`

4. Execute cells sequentially and observe the outputs

## Expected Outcomes

- ✅ Cleaned dataset with proper data types and handling of missing values
- ✅ Comprehensive EDA report with multiple visualizations
- ✅ Statistical summary of the dataset
- ✅ Understanding of data patterns and distributions
- ✅ Code documentation and explanations

## Common Challenges & Solutions

| Challenge | Solution |
|-----------|----------|
| Missing values | Use appropriate imputation or removal based on context |
| Incorrect data types | Use `pd.to_datetime()` or `.astype()` for conversion |
| Outliers | Visualize with box plots and decide handling strategy |
| Unclear patterns | Create multiple visualizations from different angles |

## Next Steps

After completing Level 1, you'll be ready for Level 2 where you'll apply these cleaned datasets to build predictive models using statistical and machine learning techniques.

## References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)

---

**Project Duration**: 1-2 weeks  
**Difficulty Level**: Beginner  
**Prerequisites**: Basic Python knowledge
