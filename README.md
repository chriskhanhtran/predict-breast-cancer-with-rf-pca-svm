# Predict Breast Cancer with Random Forest, PCA and SVM

Full project: [link](https://github.com/chriskhanhtran/predict-breast-cancer-with-rf-pca-svm/blob/master/Predict%20Breast%20Cancer%20with%20Random%20Forest%2C%20PCA%20and%20SVM.ipynb).

In the first part of this project, I will perform exploratory data analysis to better understand each of 30 original features and how they might be associated with cancer.

Next, I am going to select 5 best features for my model using univariate feature selection, and perform Random Forest classifier. The accuracy rate of this model is 97%.

In addition, I use PCA to find the two principle components and create visualization based on these two variables. The visualization shows that with only two variables, we can clearly separate the data between cancer and no cancer. Finally, I preform Support Vector Machines model to predict cancer based on PCA. The accuracy rate of this SVM model is 95%.

My purpose of doing this project is to learn how to mine the data by exploring each feature, select features for my models, and perform various machine learning models.

I hope you enjoy this project. If you have any questions, please contact me at tranduckhanh96@gmail.com. Thank you for reading!

## Data Set Information

The [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)) is obtained from UCI Machine Learning Repository. Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.

Number of Instances: 569

Number of Attributes: 30 numeric, predictive attributes and the class
