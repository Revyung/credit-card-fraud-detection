# Credit Card Fraud Detection
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.  

The datasets contains transactions made by credit cards in September 2013 by european cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.  

The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection.  

For more details, visit [here](https://www.kaggle.com/mlg-ulb/creditcardfraud)

# Things included in the notebook:
- Exploration of a realistic credit card transaction dataset.
- Explanation of the deficiency of accuracy in interpreting the classification power of a supervised learning algorithm.
- The use of Precision-recall curve and its AUC score metric.
- The inadequacy of Receiver Operating Characteristic when it comes to the small sample size of minority class.
- How synthetic data generation of the minority class (up-sampling) can help.
- Introduction to SMOTE (Synthetic Minority Over-sampling Technique) in imblearn library.
- Why cross validation should be done before SMOTE.
- The improvement of pr-score from 0.6393 to 0.7421.

# Reference:
[N. V. Chawla et al. (2002). SMOTE: Synthetic Minority Over-sampling Technique](https://arxiv.org/pdf/1106.1813.pdf)
