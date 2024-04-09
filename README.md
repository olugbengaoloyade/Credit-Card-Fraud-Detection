## CREDIT CARD FRAUD
Credit card fraud, a prevalent form of identity fraud, occurs when an individual utilizes another person's card to make unauthorized purchases.

According to [bankrate.com](https://www.bankrate.com/finance/credit-cards/credit-card-fraud-statistics/), the Federal Trade Commission (FTC) received approximately 390,000 reports of credit card fraud in the year 2021.

In December 2022, the Nilson Report, a reputable entity monitoring the payments industry, forecasted that the United States of America could potentially incur losses totaling $165.1 billion over the subsequent ten-year period.

Given the significant financial implications, it is imperative that we address this growing menace effectively.

### Dataset Attributes

V1 - V28 : Principal components derived from PCA, represented numerically in this dataset.

Time : Contains the seconds elapsed between each transaction and the first transaction in the dataset

Amount : Transaction amount.

Class: Indicates whether the transaction is fraudulent or legitimate, represented by values of 1 or 0 respectively.

Data used is the [Credit Card Fraud Detection Dataset from Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data).

## Requirements:

- pyenv with Python: 3.9.4

### Setup

Use the requirements file in this repo to create a new environment.

```BASH
make setup

#or

pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

The `requirements.txt` file contains the required libraries 
