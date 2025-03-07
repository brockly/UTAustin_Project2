# Machine Learning Project: Personal Loan Campaign

## Overview
This repository contains the **Personal Loan Campaign** machine learning project, completed as part of the Great Learning program in partnership with UT Austin. The goal of this project is to leverage machine learning techniques to identify potential customers for a personal loan product based on historical customer data.

## Context
AllLife Bank, a growing US bank, aims to convert more of its existing liability (depositor) customers into borrowers (asset customers). Previous marketing campaigns have shown a conversion rate of over 9%, motivating the bank's marketing department to use targeted strategies to further improve results. The purpose of this project is to build a predictive model to identify customers likely to accept personal loan offers.

## Objective
Develop a machine learning model to help the marketing department at AllLife Bank identify customers with high potential for converting from liability customers (depositors) to asset customers (personal loan takers). The project includes:

- Identifying relevant factors influencing the likelihood of loan acceptance.
- Building and evaluating predictive models to increase the campaign's success rate.

## Data Description
The dataset includes the following customer attributes:

| Feature      | Description                                                                 |
|--------------|-----------------------------------------------------------------------------|
| `Income`     | Annual income in thousand dollars                                           |
| `Age`        | Customer age in years                                                       |
| `Experience` | Professional experience in years                                            |
| `ZIP Code`   | Customer’s ZIP code                                                         |
| `Family`     | Family size                                                                 |
| `CCAvg`      | Average monthly credit card spending (in thousand dollars)                  |
| `Education`  | Education level (1: Undergrad, 2: Graduate, 3: Advanced/Professional degree)|
| `CCAvg`      | Average credit card spending per month (in thousand dollars)                |
| `Family`     | Family size                                                                 |
| `Online`     | Uses internet banking (0=No, 1=Yes)                                         |
| `CreditCard` | Uses credit card issued by the bank (0=No, 1=Yes)                           |
| `Mortgage`   | Value of house mortgage if any (in thousand dollars)                        |
| `Personal Loan`| Accepted the personal loan offer (0=No, 1=Yes)                             |

## Analysis & Modeling
- Data exploration and preprocessing
- Model training using various algorithms (Logistic Regression, Decision Trees, Random Forest, etc.)
- Evaluation and selection of the best-performing model

## Tools and Libraries
- Python 3.x
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

## How to Use
1. Clone this repository to your local environment:
```bash
git clone [repository_url]
```

2. Open the Jupyter notebook file provided ('''bash .ipynb''') in the repository and execute the Python cells sequentially to run the analysis.

---

**Author:** Alex Brockman
**Course:** Machine Learning, Great Learning @ UT Austin  
**Date:** April 2024

