# Credit-card-Fraud-Detection

# Credit Card Fraud Detection

## Overview
This repository contains Python code for analyzing credit card transaction data to detect fraudulent transactions using statistical measures and data separation techniques.

## Contents
- `credit_card_fraud_detection.ipynb`: Jupyter Notebook containing the Python code for data analysis and fraud detection.
- `README.md`: This file, providing an overview of the project.

## Requirements
- Python 3.x
- Pandas
- Jupyter Notebook

## Code Description
### Data Analysis
- The code begins by loading the credit card transaction dataset.
- It checks for missing values in the dataset and examines the distribution of transaction classes (fraudulent and legitimate).

### Data Preprocessing
- The dataset is separated into two groups: legitimate and fraudulent transactions for further analysis.
- Statistical measures (such as mean, describe) for transaction amounts in both groups are calculated and compared.

### Data Modeling
- A comparison between the statistical measures of legitimate and fraudulent transactions is performed.
- A new dataset is created by concatenating a sample of legitimate transactions with all fraudulent transactions.

## Usage
1. Clone the repository: `git clone https://github.com/your-username/credit-card-fraud-detection.git`
2. Install the required dependencies: `pip install pandas jupyter`
3. Open and run the Jupyter Notebook `credit_card_fraud_detection.ipynb`.
4. Follow the step-by-step code blocks to analyze and detect fraudulent transactions.

## Important Notes
- Ensure the dataset file ('credit_card_data.csv') is placed in the same directory as the notebook.
- This code serves as a basic example and might require further enhancements for a production environment.

## Dataset
The dataset used in this analysis contains credit card transaction data with features like 'Amount', 'Class' (0 for legitimate and 1 for fraudulent transactions), and others. Please note that the actual dataset used is not provided in this repository due to confidentiality reasons.

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
