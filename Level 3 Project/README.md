# Level 3 Project: Classification & Advanced Machine Learning

## Overview
This advanced project applies machine learning techniques to classification problems. Students will build multiple classification models, perform hyperparameter tuning, evaluate complex metrics, and learn to make informed decisions about model selection and optimization. This is the capstone project integrating all previous learning.

## Project Objectives
- **Classification Modeling**: Build and compare multiple classification algorithms
- **Advanced Preprocessing**: Handle categorical variables, feature scaling, encoding
- **Hyperparameter Tuning**: Optimize model performance using grid search and cross-validation
- **Performance Evaluation**: Master classification metrics (accuracy, precision, recall, F1, ROC-AUC)
- **Model Deployment**: Prepare models for real-world predictions

## Tasks

### Task 1: Customer Churn Prediction (Classification)
**File**: `Task 1.ipynb`

**Dataset**: Customer Churn Dataset

**Objective**: Build a classification model to predict whether a customer will churn (leave) the service

**Key Activities**:
- Load and explore customer churn dataset
- Handle categorical variables (encoding, label encoding, one-hot encoding)
- Feature scaling and normalization
- Data preprocessing and feature engineering
- Train multiple classification models:
  - Logistic Regression
  - Decision Trees
  - Random Forest
  - Other classifiers as applicable
- Model comparison and evaluation
- Hyperparameter tuning with Grid Search
- Final model selection and validation

**Skills Covered**:
- Categorical variable encoding techniques
- Feature scaling (StandardScaler, MinMaxScaler)
- Multiple classification algorithms
- Cross-validation strategies
- Hyperparameter tuning with GridSearchCV
- Classification metrics:
  - Accuracy, Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC Score
- Model comparison and selection
- Predictions on new data

**Key Deliverables**:
- Trained classification models
- Model performance comparison
- Confusion matrices for each model
- ROC curves and AUC scores
- Feature importance analysis
- Final model with best performance

---

### Task 2: Additional Classification Analysis
**File**: `Task 2.ipynb`

**Activities**:
- Extended model evaluation techniques
- Advanced feature engineering
- Ensemble methods exploration
- Model interpretation and explanation

---

### Task 3: Sentiment Analysis & Advanced Classification
**File**: `Task 3.ipynb`

**Dataset**: Sentiment Dataset

**Objective**: Apply text processing and classification to sentiment prediction

**Key Activities**:
- Text data preprocessing and cleaning
- Feature extraction from text:
  - TF-IDF (Term Frequency-Inverse Document Frequency)
  - Count Vectorization
- Building classification models for sentiment
- Model evaluation on text data
- Advanced techniques and optimization

**Skills Covered**:
- Text preprocessing (tokenization, stemming, lemmatization)
- Text feature extraction methods
- Text classification with ML algorithms
- Natural Language Processing basics

---

## Dataset Information

**Customer Churn Dataset**:
- Customer service/telecommunications data
- Features: Account length, service usage, customer service calls, plan information
- Target: Churn (Yes/No)
- Categorical and numerical mixed features
- ~20 features for modeling

**Sentiment Dataset**:
- Text-based customer reviews or feedback
- Target: Sentiment classification (positive/negative or multi-class)
- Unstructured text data
- Requires text preprocessing

## Technologies & Tools

| Tool | Purpose |
|------|---------|
| **Python** | Programming language |
| **Pandas** | Data manipulation |
| **NumPy** | Numerical operations |
| **Scikit-learn** | Machine learning algorithms |
| **Matplotlib** | Visualization |
| **Seaborn** | Statistical visualization |
| **Scipy** | Statistical functions |
| **Grid Search** | Hyperparameter optimization |

## Key Concepts

### Classification Algorithms

**Logistic Regression**
- Linear classifier for binary problems
- Probability-based predictions
- Interpretable coefficients

**Decision Trees**
- Non-linear classifier
- Easy to interpret
- Prone to overfitting

**Random Forest**
- Ensemble of decision trees
- Better generalization
- Feature importance ranking

### Essential Classification Metrics

**Accuracy**
- Proportion of correct predictions
- Can be misleading with imbalanced data
- Formula: (TP + TN) / (TP + TN + FP + FN)

**Precision**
- True Positives / All Predicted Positives
- "Of the customers we predicted would churn, how many actually did?"
- Important when false positives are costly

**Recall (Sensitivity)**
- True Positives / All Actual Positives
- "Of all customers who actually churned, how many did we identify?"
- Important when false negatives are costly

**F1-Score**
- Harmonic mean of Precision and Recall
- Balanced metric for imbalanced datasets
- Formula: 2 × (Precision × Recall) / (Precision + Recall)

**ROC-AUC**
- Area Under the Receiver Operating Characteristic Curve
- Measures performance across all classification thresholds
- Range: 0-1 (higher is better)

### Confusion Matrix

```
              Predicted Negative    Predicted Positive
Actual Negative    TN                  FP
Actual Positive    FN                  TP
```

- **TP (True Positive)**: Correctly predicted positive
- **TN (True Negative)**: Correctly predicted negative
- **FP (False Positive)**: Incorrectly predicted positive (Type I error)
- **FN (False Negative)**: Incorrectly predicted negative (Type II error)

### Hyperparameter Tuning

**Grid Search**:
- Exhaustive search over specified parameter values
- Finds optimal hyperparameter combination
- Computationally intensive but thorough

**Cross-Validation**:
- K-fold cross-validation splits data k times
- Prevents overfitting and provides robust evaluation
- Typically 5-10 folds

## How to Run

1. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```

2. Run notebooks in recommended order:
   - `Task 1.ipynb` - Core classification project
   - `Task 2.ipynb` - Extended analysis
   - `Task 3.ipynb` - Sentiment analysis

3. Execute cells sequentially and examine outputs

## Expected Outcomes

- ✅ Multiple trained classification models
- ✅ Model performance comparison table
- ✅ Confusion matrices for all models
- ✅ ROC curves and AUC scores
- ✅ Hyperparameter tuned best model
- ✅ Feature importance analysis
- ✅ Prediction examples on test data
- ✅ Comprehensive analysis report
- ✅ Well-documented, reproducible code

## Model Selection Guidelines

### Choose Based On:

**Logistic Regression**
- When interpretability is crucial
- With limited computational resources
- As a baseline model

**Decision Trees**
- For non-linear relationships
- With categorical variables
- When tree interpretation is valuable

**Random Forest**
- For best predictive performance
- When feature importance matters
- With larger datasets

### Evaluation Strategy:
1. Train all models
2. Compare metrics on validation set
3. Perform hyperparameter tuning on top candidates
4. Final evaluation on test set
5. Select based on business requirements

## Common Challenges & Solutions

| Challenge | Solution |
|-----------|----------|
| Imbalanced classes | Use stratified split, class weights, or resampling |
| Poor model performance | Feature engineering, more data, ensemble methods |
| Overfitting | Cross-validation, regularization, simpler models |
| Categorical features | One-hot encoding or label encoding appropriately |
| Text data formatting | Clean, tokenize, vectorize before modeling |
| Slow hyperparameter tuning | Use RandomizedSearchCV or reduce parameter grid |

## Advanced Techniques to Explore

- **Imbalanced Learning**: SMOTE, class weights
- **Ensemble Methods**: Voting, Stacking
- **Feature Selection**: Recursive Feature Elimination (RFE)
- **Calibration**: Probability calibration for better confidence
- **Interpretability**: SHAP values, permutation importance
- **Cross-validation**: Stratified K-fold, time-series split

## Model Deployment Considerations

- Feature scaling consistency
- Categorical encoding mapping
- Threshold adjustment for business needs
- Monitoring model performance over time
- Retraining strategies

## Workflow Diagram

```
Data Loading
    ↓
EDA & Feature Understanding
    ↓
Data Preprocessing (handling missing values, scaling, encoding)
    ↓
Train-Test Split (Stratified)
    ↓
Feature Scaling & Encoding
    ↓
Model Training (Multiple Models)
    ↓
Initial Evaluation
    ↓
Hyperparameter Tuning
    ↓
Final Evaluation on Test Set
    ↓
Model Selection & Interpretation
    ↓
Predictions & Deployment
```

## Performance Benchmarks

### Typical Good Performance Ranges:
- **Accuracy**: 80-95% (depends on dataset complexity)
- **Precision**: 75-90% (depends on business tolerance)
- **Recall**: 75-90% (depends on importance of catching all positives)
- **F1-Score**: 0.8-0.95
- **ROC-AUC**: 0.85-0.95

*Note: These vary based on dataset characteristics and business requirements*

## References

- [Scikit-learn Classification Metrics](https://scikit-learn.org/stable/modules/model_evaluation.html#classification-metrics)
- [Classification Algorithms Guide](https://scikit-learn.org/stable/supervised_learning.html)
- [Grid Search Documentation](https://scikit-learn.org/stable/modules/grid_search.html)
- [ROC-AUC Explanation](https://towardsdatascience.com/understanding-auc-roc-curve-68b2303cc9c5)
- [Confusion Matrix Guide](https://www.dataschool.io/simple-guide-to-confusion-matrix-terminology/)

## Next Steps After Level 3

- **Deep Learning**: Neural networks for complex patterns
- **Time Series**: Forecasting and sequential data
- **Clustering**: Unsupervised learning techniques
- **Dimensionality Reduction**: PCA, t-SNE
- **Production ML**: Model serving and monitoring
- **Advanced NLP**: Transformers, embeddings

---

**Project Duration**: 3-4 weeks  
**Difficulty Level**: Advanced/Intermediate  
**Prerequisites**: Level 1 & 2 completion, statistics knowledge  
**Key Takeaway**: Building production-ready machine learning models with rigorous evaluation and optimization
