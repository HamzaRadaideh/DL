# Keras API Project Exercise

## Overview

This project utilizes a subset of the LendingClub dataset to build a model that predicts whether a borrower will repay their loan. The dataset includes various features related to the borrower's financial history, loan details, and personal information.

## Data

The dataset used in this project is a subset of the LendingClub data, which contains historical loan data with information on whether or not the borrower defaulted (charge-off). The goal is to predict loan repayment status based on the features provided.

## Data Source

The data can be obtained from Kaggle: [LendingClub DataSet](https://www.kaggle.com/wordsforthewise/lending-club)

## Project Goals

Given historical data on loans with information on whether or not the borrower defaulted, the goal is to build a model that can predict whether a borrower will repay their loan. This allows for the assessment of new potential customers and their likelihood to repay the loan.

## Data Dictionary

| LoanStatNew                  | Description                                                                                       |
|------------------------------|---------------------------------------------------------------------------------------------------|
| loan_amnt                    | The listed amount of the loan applied for by the borrower.                                        |
| term                         | The number of payments on the loan. Values are in months and can be either 36 or 60.              |
| int_rate                     | Interest Rate on the loan.                                                                       |
| installment                  | The monthly payment owed by the borrower if the loan originates.                                 |
| grade                        | LC assigned loan grade.                                                                          |
| sub_grade                    | LC assigned loan subgrade.                                                                       |
| emp_title                    | The job title supplied by the borrower when applying for the loan.                               |
| emp_length                   | Employment length in years. Possible values are between 0 and 10.                                |
| home_ownership               | The home ownership status provided by the borrower.                                              |
| annual_inc                   | The self-reported annual income provided by the borrower during registration.                    |
| verification_status          | Indicates if income was verified by LC, not verified, or if the income source was verified.      |
| issue_d                      | The month which the loan was funded.                                                             |
| loan_status                  | Current status of the loan.                                                                      |
| purpose                      | A category provided by the borrower for the loan request.                                        |
| title                        | The loan title provided by the borrower.                                                         |
| zip_code                     | The first 3 numbers of the zip code provided by the borrower in the loan application.            |
| addr_state                   | The state provided by the borrower in the loan application.                                      |
| dti                          | Debt-to-income ratio calculated using the borrower’s total monthly debt payments.                |
| earliest_cr_line             | The month the borrower's earliest reported credit line was opened.                               |
| open_acc                     | The number of open credit lines in the borrower's credit file.                                   |
| pub_rec                      | Number of derogatory public records.                                                             |
| revol_bal                    | Total credit revolving balance.                                                                  |
| revol_util                   | Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit. |
| total_acc                    | The total number of credit lines currently in the borrower's credit file.                        |
| initial_list_status          | The initial listing status of the loan. Possible values are W or F.                              |
| application_type             | Indicates whether the loan is an individual application or a joint application with two co-borrowers. |
| mort_acc                     | Number of mortgage accounts.                                                                     |
| pub_rec_bankruptcies         | Number of public record bankruptcies.                                                            |

## Project Structure

### Section 1: Exploratory Data Analysis (EDA)
- **Task:** Create visualizations and summary statistics to understand the data and its distributions.

### Section 2: Data PreProcessing
- **Task:** Handle missing values, remove unnecessary columns, and convert categorical variables to dummy variables.

### Section 3: Model Building and Evaluation
- **Task:** Build and train a neural network using Keras to predict loan repayment. Evaluate the model's performance using various metrics.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow
- keras

## Installation

To install the necessary libraries, run:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow keras
```

## Usage

### Data Preparation
- Load the dataset and perform data preprocessing steps, including handling missing values and converting categorical variables.

### Model Training
- Build and train a neural network using Keras.

### Model Evaluation
- Evaluate the model using validation loss, accuracy, classification report, and confusion matrix.

### Prediction
- Predict the loan repayment status for a new customer and check the actual repayment status.

## Results

The project successfully demonstrates the use of neural networks for classification problems in financial data. The model provides insights into loan repayment predictions, which can be useful for financial institutions in assessing loan applications.

## Conclusion

This project highlights the application of neural networks for predicting loan repayment status. The developed model can aid financial institutions in making informed decisions about loan approvals.

## References

- [LendingClub DataSet on Kaggle](https://www.kaggle.com/wordsforthewise/lending-club)
- [Keras Documentation](https://keras.io/)
- [TensorFlow Documentation](https://www.tensorflow.org/)
