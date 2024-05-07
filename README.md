# Bookbinders-Marketing-Analysis
We used multiple predictive modeling techniques to forecast customer responses to marketing initiatives.

## Background
This case study explores the strategic and operational challenges Bookbinders Book Club (BBBC) faces amid the shifting dynamics of book retail and distribution since its establishment in 
1986. With the rise of superstores and online retailing altering consumer preferences and intensifying competitive pressures, BBBC has been prompted to innovate its customer
engagement and sales strategies. Utilizing a robust database of 500,000 readers, BBBC is advancing into database marketing and predictive modeling to boost the efficiency of its direct
marketing techniques.



## Introduction
BBBC wants to determine which predictive model is best at improving the efficacy of direct mail programs. Their last model, which consisted of 20,000 customers across 
Northeastern USA that received a copy of the mailing list and a brochure for The History of Florence. Of the 20,000 clients that received the  mailing list, 9.03% purchased the book.

**BBBC wants to maximize the number of clients that buy the book**, and is exploring 3 models that may allow it to do so: linear regression, logistic regression, and SVM.

## Analysis
We first cleand and prepare the data, then we build machine learning models. Our analysis explores logistic regression, **support vector machines (SVM)** with 3 different kernels, and **linear regression (lm)** using R programming, with a focus on classification methods and their underlying assumptions. We had to create balanced datasets and compared the rsults from the balanced and unbalanced models.

## Findings
- Logistic Regression
Accuracy: 89.5% Sensitivity: 94.5% Specificity: 37.3%

- Balanced Logistic Regression
Accuracy: 74% Sensitivity: 82.4% Specificity: 65.7%

- SVM Model Linear Unbalanced
Accuracy: 89.5% Sensitivity: 95% Specificity: 34.5% AUC: 78.5%

- SVM Model Balanced
Accuracy: 73.5% Sensitivity: 82.8% Specificity: 64.2% AUC: 81.6%

## Conclusion and Recommendations
Since we were trying to predict people who purchase the book (Specificity), we decided to choose **Logistic Regression (Balanced)**, as the best model, due to their high accuracy and specificity. It was also the model that performed the best and gave the company more profit. 
The best predictors were `Female` and `P_Art`, therefore we suggest the company mainly target women who have already bought Art books. BBBC should also use Balanced Logistic Regression for future Analysis.
To simplify and automate the recommended methods for future modeling efforts at the company we would suggest BBBC collect more data from their clients (more observations), and add more variables to the survey such as kids or marital status, to be able to have more predictors and therefore do a better classification analysis. 










