### This is a experiment documenting how to handle skewed dataset in reality, especially in the domain of fraud detection.

# Things included in the notebook:
- Exploration of a realistic credit card transaction dataset.
- Explanation of the deficiency of accuracy in explained the classification power of supervised learning algorithm.
- The use of Precision-recall curve and its AUC score metric.
- The inadequacy of Receiver Operating Characteristic when it comes to the small sample size of minority class
- How synthetic data generation of the minority class (up-sampling) can help.
- Introduction to SMOTE (Synthetic Minority Over-sampling Technique) in imblearn library
- The improvement of pr-score from 0.655 to 0.997 

# Reference:
[SMOTE: Synthetic Minority Over-sampling Technique, N. V. Chawla et al.](https://arxiv.org/pdf/1106.1813.pdf)