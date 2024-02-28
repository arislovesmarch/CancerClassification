Hi!

This project aims to classify whether a breast tumor is malignant or benign by using a Logistic Regression and a SVM model from scikit-learn.
The model uses the Kaggle Breast Cancer dataset from https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset/data

The following libraries are needed:
- pandas
- sklearn
(- seaborn ) if more data insights is needed, I used seaborn at first but did not proceed to include it in the project as the features were all showing patterns and dropping some multicollinear features with VIF, RFE & PCA Techniques did not result in better scores
