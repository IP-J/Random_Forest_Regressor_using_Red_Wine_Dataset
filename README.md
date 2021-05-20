# Random_Forest_Regressor_using_Red_Wine_Dataset
Random Forest Regressor implementation on full dimensional and reduced-dimensional data
In this notebook, we will train two Random Forest models using the original data and using the reduced-dimensional data respectively

In the UCI Machine Learning Repository website above, there is a dataset on red wine:
https://archive.ics.uci.edu/ml/datasets/wine+quality
which has 12 attributes and a column that describes the quality rating of the wine. For any new test instance, we want our regressor to be able to predict this value. 
In this notebook, we will work on the red wine data file only. The winequality-red.csv can be downloaded directly from the link below: https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/

The tasks done in this notebook are as follows.
1. Reading in the contents of the file and perform the usual data inspection and cleaning.doing a 85/15 random split to form the training and testing sets. 
   Implementing a Random Forest regressor to predict the wine quality values of instances in the training and test sets. 
   Reporting the MAEs of the predictions on the training and test sets and plotting the prediction results and using histogram(s) to show the distributions of the raw errors of the predictions for both sets.
2. Extracting the feature importances from the training process and trimming the feature dimension of the data. We are retaining only those features whose importance values are above 5% (i.e., 0.05). 
   Reporting what features were retained and what features were removed in the above process.
3. Repeating the training and prediction processes above on the reduced-dimensional data.
4. Finally, comparing the performance of the two models of our regressor.
