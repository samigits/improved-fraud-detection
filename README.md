# IMPROVED FRAUD DETECTION

## Overview
This project aims to create accurate and strong fraud detection models that handle the unique challenges of both types of transaction data. It also includes using geolocation analysis and transaction pattern recognition to improve detection. Good fraud detection greatly improves transaction security.


## Methodology 
### Exploratory Data Analysis (EDA)
EDA was conducted at both univariate and bivariate levels:
    1. Class imbalance was visualized, revealing significant skew toward non-fraudulent cases in both datasets.
    2. Distributional patterns of age, transaction time, and purchase value were explored.
    3. Boxplots and correlation heatmaps highlighted potential associations between features and fraud likelihood.

## Best Performing Fraud Detection With SHAP
SHAP ( Shapley Additive Explanations) was applied to identify the best-performing fraud detection model. The goal is to identify the most influential features contributing to fraud prediction and provide both global and local interpretability.
    SHAP Summary Plot was used to analyze both the direction and magnitude of feature impact.

    SHAP Bar Plot (mean absolute SHAP values) was used to understand the global importance of features by averaging their contribution across all predictions.

## Conclusion
HAP explainability techniques have provided critical insight into the model’s decision-making process.
The most important drivers of fraud include user demographics (age, gender), traffic source, and
browser choice. These insights can guide further feature engineering, risk profiling, and fraud prevention
strategies.

## How to Set Up
1. **Clone this repository**:
    ```bash
    git clone https://github.com/samigits/improved-fraud-detection.git
    cd improved-fraud-detection
    ```
2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Run analysis notebook**:
    ```bash
    jupyter notebook
    ```
4. **Replace `path_to_your_file.csv`** in the code with your actual CSV file path.
## 📂 Folder Structure
credit_risk_probability_model/  
├── .github/workflows/ci.yml   # For CI/CD

├── data/                       

│   ├── raw/            

│   └── processed/             

├── notebooks/

│   └── eda.ipynb

│   └── model_train.ipynb          

├── src/

├── tests/

│   └── test_data_processing.py 

├── Dockerfile

├── docker-compose.yml

├── requirements.txt

├── .gitignore

└── README.md
