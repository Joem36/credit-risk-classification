# credit-risk-classification
For reference, activities were utilized from previous classes to help navigate me through this data set 


- Data cleaning and preparation involved organizing the raw data.
- The dataset encompassed various financial attributes, such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.


- Utilized Logistic Regression, a supervised learning classification model, to forecast the probability of loan creditworthiness.
- The model was trained to distinguish between healthy loans (0) and high-risk loans (1).

Machine Learning Model 1:
- Accuracy revealed 18679 true positive and 558 true negative outcomes.
- Precision indicated better performance in predicting healthy loans (precision 1) compared to high-risk loans (precision 0.87).
- Recall demonstrated superior identification of healthy loans (recall 1) over high-risk loans (recall 0.89).
- Support indicated an imbalance in the training data, with 18759 healthy loans versus 625 high-risk loans.

Machine Learning Model 2:
- Accuracy showcased 55945 true positive and 55954 true negative results.
- Precision demonstrated equal performance in predicting both healthy loans (precision 0.99) and high-risk loans (precision 0.99).
- Recall illustrated similar effectiveness in identifying healthy loans (recall 0.99) and high-risk loans (recall 0.99).
- Support indicated a balanced distribution in the training data, with 56277 instances for both healthy and high-risk loans.

Summary:
- The recommendation leans towards utilizing 'Machine Learning Model 2' due to its balanced reported scores and robust performance in Accuracy, Precision, and Recall for both loan categories.
- Post-resampling, 'Machine Learning Model 2' showcased heightened performance, making it better suited for predicting loan risks and classifying them as either healthy or high-risk.
