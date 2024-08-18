# Credit Risk Classification Using Bank Loan Dataset

## Context

This project focuses on analyzing a dataset of 1,000 entries provided by Prof. Hofmann, where each entry represents a person who takes a credit from a bank. Each individual is classified as a good or bad credit risk based on a set of attributes. The original dataset was highly complex, using a system of categories and symbols that made it difficult to interpret. Therefore, I developed a Python script to convert it into a more readable CSV format, excluding some columns that were either obscure or deemed unimportant.

- **Original Dataset Source**: [Link to the dataset](#)

## Dataset Content

The converted dataset includes the following attributes:

- **Age** (numeric): The age of the person.
- **Sex** (text): Gender of the person (`male`, `female`).
- **Job** (numeric):
  - `0`: Unskilled and non-resident
  - `1`: Unskilled and resident
  - `2`: Skilled
  - `3`: Highly skilled
- **Housing** (text): Housing status (`own`, `rent`, `free`).
- **Saving Accounts** (text): Saving account status (`little`, `moderate`, `quite rich`, `rich`).
- **Checking Account** (numeric, in DM - Deutsch Mark): Balance in the checking account.
- **Credit Amount** (numeric, in DM): The credit amount taken.
- **Duration** (numeric, in months): Duration of the credit.
- **Purpose** (text): Purpose of the credit (`car`, `furniture/equipment`, `radio/TV`, `domestic appliances`, `repairs`, `education`, `business`, `vacation/others`).

## Work Done

### Data Preparation

- **Null Values**: Checked for and removed null values to clean the dataset.
- **Unique Values**: Analyzed unique values in each column and replaced text categories with numeric equivalents to streamline model processing.

### Exploratory Data Analysis (EDA)

- **Correlation Matrix & Heatmap**: Visualized the correlation between variables to identify relationships.
- **Histograms**: Plotted histograms to explore the distribution of various attributes.
- **Boxplots**: Used boxplots to understand the spread and outliers in numerical data.
- **Distribution Plot**: Specifically analyzed the distribution of credit amounts.

### Machine Learning Models

1. **Data Splitting**: Split the dataset into training and testing sets to evaluate model performance.
2. **Modeling**: Applied the following models to classify credit risk:
   - **Logistic Regression**: Evaluated using a classification report and checked for accuracy on both training and testing sets to identify potential underfitting or overfitting.
   - **Support Vector Classifier (SVC)**
   - **Random Forest**
   - **K-Nearest Neighbors (KNN)**
   - **Gaussian Naive Bayes (GaussianNB)**
3. **Prediction**: Tested the models with new data inputs to predict credit risk.


