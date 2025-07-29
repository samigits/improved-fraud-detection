# IMPROVED FRAUD DETECTION

## Overview
This project aims to create accurate and strong fraud detection models that handle the unique challenges of both types of transaction data. It also includes using geolocation analysis and transaction pattern recognition to improve detection. Good fraud detection greatly improves transaction security.

## How to Setup
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