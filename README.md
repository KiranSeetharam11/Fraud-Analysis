# Fraud Transaction Analysis

Frauds are a common instance in every company that handles transactions in a high volume, even though the ratio of fradulent transactions to non fradulent is very less, it is still advisable to identify the fradulent transactions as soon as possible, so that we can attend to the problem quickly.

The objective of this project is to develop a Machine Learning Model to help classify the transactions into fraud and non-fradulent.

We have used Randomforest Classifier to help us classify if a transaction is fraudulent or not.





## Data Background
The dataset consists of 2 Million transactions with around 5000 as fraudulent.

Basic Data Cleaning is taken forward to avoid columns that have no correlation with the final prediction model.

A data dictionary file is added to give definition to every column heading.
The dataset can be found in the follwing link - [Dataset](https://drive.google.com/file/d/1RFDYVS5KvdejFqk_IAit0xMLMhKIVYoT/view?usp=sharing)

## Run Locally

To run this project locally, ensure you have the following libraries installed:

```bash
  pip install pandas
  pip install numpy
  pip install scikit-learn
  pip install matplotlib
  pip install seaborn
```
    
## Structure of the project

This project is used by the following companies:

### Data Cleaning
- Check and handle Null values
- Check correlation of feature columns and drop unnecessary ones

### Feature Engineering
- Features are encoded into integers.
- The dataset is imbalanced. Hence, SMOTE is used to generate samples for the minority class.

### Model Training
- The data is split into training and test sets.
- A RandomForestClassifier is used to train the model, and the classification report is used for analysis

### Model Optimization
- RandomSearch is employed to enhance model parameters.

### Performance
- After hyper parameter tuning , the f1 score obtained was 1 with model score as 0.99998



## ER Diagram

![ER Diagram](https://github.com/KiranSeetharam11/Fraud-Analysis/blob/main/Concept%20map%20(2).png)
