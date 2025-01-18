# Customer Churn Analysis

This project investigates customer churn for a telecommunications company using machine learning models. The goal is to understand the factors contributing to customer churn and build predictive models to help the company improve customer retention strategies.

## Table of Contents
- [Motivation](#motivation)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Future Improvements](#future-improvements)
- [Author](#author)
- [License](#license)

## Motivation
Customer churn has a significant impact on profitability in the telecommunications industry. Understanding and predicting customer churn allows businesses to take proactive steps to retain customers. This project aims to analyze customer data, identify key drivers of churn, and build predictive models to enhance decision-making.

## Data
The dataset used in this project is the **Telco Customer Churn** dataset, available on Kaggle:
[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

The dataset includes customer demographics, account information, and service usage details. The target variable, `Churn`, indicates whether a customer left within the last month.

## Methodology
### Steps
1. **Data Cleaning**:
   - Handled missing values.

2. **Exploratory Data Analysis (EDA)**:
   - Visualized correlations between churn and various features.
   - Examined tenure and monthly charges in relation to churn.
3. **Feature Engineering**:
   - Created new features, such as `MonthlyContractInteraction` and `ChargesPerMonth`.
3. **Model Building and Evaluation**:
   - Implemented Logistic Regression, Random Forest Classifier, and Support Vector Machine (SVM).
   - Used accuracy, confusion matrices and ROC-AUC for performance evaluation.

## Results
- Logistic Regression slightly outperformed other models with high accuracy and interpretability.
- Key features influencing churn include contract type, tenure, and monthly charges.
- Feature importance differs between logistic regression coefficients and random forest rankings.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, seaborn, matplotlib, and more
- **Environment**: Jupyter Notebook

## Usage
To view the complete notebook, visit the HTML version on my portfolio:  
[Customer Churn Analysis Notebook](https://mqanaa.github.io/Customer%20churn%20analysis.html)

### Steps to Run Locally
1. Clone this repository.
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Churn_Analysis.ipynb
   ```

## Future Improvements
- Explore additional predictive models such as XGBoost.
- Perform hyperparameter tuning for improved accuracy.
- Investigate further customer segmentation strategies.

## Author
Anni Aalto 
GitHub: [mqanaa](https://github.com/mqanaa)


