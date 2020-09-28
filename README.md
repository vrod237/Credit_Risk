# Credit_Risk

## Project Overview

- Implement machine learning models.
- Use resampling to attempt to address class imbalance.
- Evaluate the performance of machine learning models.




## Resources
- Data Source: [Sample Data](https://github.com/vrod237/Credit_Risk/blob/master/Resources/LoanStats_2019Q1.csv)


- Software: Python, Jupyter Notebook

## Summary

- [Credit Risk Ensemble](https://github.com/vrod237/Credit_Risk/blob/master/credit_risk_ensemble.ipynb)

    - Import data using pandas.
    - The count for low risk loans are 68,470 and the count for high risk loans are 347.
    - Split data into training and testing samples using train test split method.
    - Used Balanced Random Forest Classifier and Easy Ensemble AdaBoost classifier to resample data.
	  - Used confusion matrix to display table of true positives, false positives, true negatives, and false negatives.
	  - Found the accuracy score for all the models.
	  - Print the imbalanced classification report.


- [Credit Risk Resampling](https://github.com/vrod237/Credit_Risk/blob/master/credit_risk_resampling.ipynb)

    - Import data using pandas.
    - The count for low risk loans are 68,470 and the count for high risk loans are 347.
    - Split data into training and testing samples using train test split method.
    - Resampled data by using Oversampling, Undersampling and Combination (Over and Under) Sampling methods.
    - Used confusion matrix to display table of true positives, false positives, true negatives, and false negatives.
	  - Found the accuracy score for all the models.
	  - Print the imbalanced classification report.
