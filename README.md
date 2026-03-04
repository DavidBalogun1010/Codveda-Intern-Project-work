# Codveda Internship Project Work

A comprehensive 1-month internship program showcasing progressive machine learning and data science skills. This repository contains three progressive projects, each building upon the previous level's foundation.

---

## 📋 Project Overview

This internship program is structured in three levels, progressively increasing in complexity and sophistication:

| Level | Focus Area | Key Skills |
|-------|-----------|-----------|
| **Level 1** | Data Cleaning & Exploratory Data Analysis | Data preprocessing, visualization, statistical analysis |
| **Level 2** | Regression & Statistical Modeling | Linear regression, model evaluation, feature engineering |
| **Level 3** | Classification & Advanced ML | Multiple algorithms, hyperparameter tuning, text analysis |

---

## 🎯 Learning Path

### Level 1: Data Cleaning & Exploratory Data Analysis
**Location**: `Level 1 Project/`

Foundation-level project focusing on essential data science skills.

**Tasks**:
- **Task 1**: Data Cleaning & Preprocessing - Stock Price Dataset
  - File: `Task1_data_cleaning_preprocessing.ipynb`
  - Skills: Data imports, missing values handling, data type conversion
  
- **Task 2 & 3**: Exploratory Data Analysis (EDA)
  - File: `task2&3_EDA.ipynb`
  - Skills: Univariate & bivariate analysis, correlation studies, advanced visualizations

**Dataset**: Stock Price Dataset (`stock price.csv`, `stock_cleaned.csv`)

**Technologies**: Python, Pandas, NumPy, Matplotlib, Seaborn

**Key Learnings**:
- Data quality assessment
- Handling missing values and outliers
- Distribution analysis
- Statistical measures and interpretation
- Data visualization best practices

---

### Level 2: Regression & Statistical Modeling
**Location**: `Level 2 Project/`

Intermediate project introducing predictive modeling techniques.

**Tasks**:
- **Task 1**: Simple Linear Regression Analysis
  - File: `Task1.ipynb`
  - Dataset: House Price Dataset
  - Skills: Train-test split, linear regression, model evaluation metrics (R², MSE, RMSE, MAE)
  
- **Task 2**: Extended EDA & Statistical Analysis
  - File: `Task 2.ipynb`
  - Skills: Advanced statistical tests, feature relationships, complex visualizations
  
- **Task 3**: Multi-Variable Analysis & Predictions
  - File: `Task 3.ipynb`
  - Skills: Multiple regression, feature selection, cross-validation, model optimization

**Datasets**: 
- `House price.csv`
- `house Prediction Data Set.csv`

**Technologies**: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn

**Key Learnings**:
- Regression model building and interpretation
- Model evaluation and performance metrics
- Residual analysis
- Feature-target relationships
- Prediction accuracy assessment

---

### Level 3: Classification & Advanced Machine Learning
**Location**: `Level 3 Project/`

Advanced capstone project covering classification algorithms and natural language processing.

**Tasks**:
- **Task 1**: Customer Churn Prediction (Classification)
  - File: `Task 1.ipynb`
  - Dataset: Customer Churn Dataset
  - Skills: Categorical encoding, multiple classifiers (Logistic Regression, Decision Trees, Random Forest), hyperparameter tuning
  
- **Task 2**: Extended Classification Analysis
  - File: `Task 2.ipynb`
  - Skills: Ensemble methods, advanced feature engineering, model interpretation
  
- **Task 3**: Sentiment Analysis & Text Classification
  - File: `Task 3.ipynb`
  - Dataset: Sentiment Dataset
  - Skills: Text preprocessing, TF-IDF, Count Vectorization, text classification

**Datasets**:
- `churn-bigml-20.csv`, `churn-bigml-80.csv` (Churn prediction)
- `Sentiment dataset.csv`, `Sentiment_clean_dataset.csv` (Sentiment analysis)

**Technologies**: Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, NLP techniques

**Key Learnings**:
- Classification algorithms and their applications
- Categorical variable encoding
- Feature scaling and normalization
- Hyperparameter tuning with GridSearchCV
- Classification metrics (accuracy, precision, recall, F1, ROC-AUC)
- Text processing and sentiment analysis
- Model comparison and selection

---

## 📊 Datasets

All datasets are stored in the `datasets/` folder:

| Dataset | Purpose | Size |
|---------|---------|------|
| `stock price.csv`, `stock_cleaned.csv` | Level 1 - Time series analysis | - |
| `house Prediction Data Set.csv`, `House price.csv` | Level 2 - Regression modeling | - |
| `churn-bigml-20.csv`, `churn-bigml-80.csv` | Level 3 - Customer churn prediction | - |
| `iris.csv` | Classification example | - |
| `Sentiment dataset.csv`, `Sentiment_clean_dataset.csv` | Level 3 - Sentiment analysis | - |

---

## 🛠️ Technologies & Tools Used

**Programming Language**: Python 3.x

**Core Libraries**:
- **Pandas** - Data manipulation and cleaning
- **NumPy** - Numerical computations
- **Scikit-Learn** - Machine learning algorithms
- **Matplotlib** - Basic data visualization
- **Seaborn** - Statistical data visualization

**Advanced Techniques**:
- Train-test splitting
- Cross-validation
- Hyperparameter tuning (GridSearchCV)
- Feature scaling and encoding
- Text processing and NLP

---

## 📈 Skill Progression

```
Level 1: Data Fundamentals
├── Data Loading & Exploration
├── Data Cleaning & Preprocessing
└── Visualization & Statistical Analysis
        ↓
Level 2: Predictive Modeling
├── Regression Analysis
├── Model Evaluation Metrics
└── Feature Engineering
        ↓
Level 3: Advanced Machine Learning
├── Classification Algorithms
├── Hyperparameter Optimization
├── Ensemble Methods
└── Natural Language Processing
```

---

## 🚀 How to Use This Repository

### Prerequisites
Ensure you have Python 3.7+ installed and the required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Running the Projects

1. Navigate to your desired project level:
   ```bash
   cd "Level 1 Project"   # or Level 2 or Level 3
   ```

2. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Open and run the relevant notebook file (.ipynb)

4. Execute cells sequentially to follow the project workflow

---

## 📚 Key Concepts & Skills Mastered

- ✅ Data quality assessment and improvement
- ✅ Exploratory data analysis (EDA)
- ✅ Statistical analysis and hypothesis testing
- ✅ Linear and multiple regression modeling
- ✅ Classification algorithms (Logistic Regression, Decision Trees, Random Forest)
- ✅ Hyperparameter tuning and cross-validation
- ✅ Model evaluation and performance metrics
- ✅ Feature engineering and selection
- ✅ Text preprocessing and sentiment analysis
- ✅ Data visualization and storytelling

---

## 📝 Project Structure

```
Codveta Internship/
├── README.md                      (This file)
├── datasets/                      (All datasets)
│   ├── churn-bigml-*.csv
│   ├── house*.csv
│   ├── iris.csv
│   ├── Sentiment*.csv
│   └── stock*.csv
├── Level 1 Project/
│   ├── README.md
│   ├── Task1_data_cleaning_preprocessing.ipynb
│   └── task2&3_EDA.ipynb
├── Level 2 Project/
│   ├── README.md
│   ├── Task1.ipynb
│   ├── Task 2.ipynb
│   └── Task 3.ipynb
└── Level 3 Project/
    ├── README.md
    ├── Task 1.ipynb
    ├── Task 3.ipynb
    └── (additional files)
```

---

## ✨ Highlights

- **Comprehensive Learning Path**: From data basics to advanced machine learning
- **Real-World Datasets**: Working with actual datasets to build practical skills
- **Progressive Difficulty**: Each level builds upon previous concepts
- **Diverse Techniques**: Covering regression, classification, and NLP
- **Best Practices**: Following industry-standard approaches and methodologies

---

## 📖 Next Steps

- Explore each project level in the order: Level 1 → Level 2 → Level 3
- Read the individual README.md files in each project folder for detailed task descriptions
- Run each notebook and experiment with the code
- Apply learned concepts to new datasets
- Build additional projects using these techniques

---

*This internship project demonstrates fundamental to advanced machine learning concepts and best practices in data science.*
