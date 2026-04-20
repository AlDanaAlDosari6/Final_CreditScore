# German Credit Risk Classification with SMOTE

This project builds a credit risk classification pipeline using the German Credit dataset.

## Models Used
- Logistic Regression + SMOTE
- Random Forest + SMOTE
- Soft Voting Ensemble

## Features
- Preprocessing with scaling and one-hot encoding
- Class imbalance handling with SMOTE
- 10-fold cross-validation
- Threshold optimization using F1-score
- ROC curve generation
- Automatic saving of results

## Project Structure
data/ -> input dataset  
outputs/ -> saved metrics and plots  
german_credit_model.py -> main script  

## Run
```bash
python german_credit_model.py
