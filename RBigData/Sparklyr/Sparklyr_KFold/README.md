# Big Data: K-Fold CV ML Classifiers with Apache Spark using Sparklyr

<br>

This project is about an application of how to use k-fold CV ML Classifiers with Apache Spark using Sparklyr. The main results obtained are presented here, providing a clear guideline that identifies the classic steps in the modeling process, possible to adapt to any other equivalent database. The key sparklyr functions and scripts used are proporcionated, allowing the reader to consult the appropriate bibliography and tutorial examples clearly and directly.

Cross-validation is a statistical method used to estimate the skill of machine learning models. It is used in machine learning to compare and select a model because it is easy to understand, easy to implement, and results in skill estimates that generally have a lower bias than other methods.

Aside from selection bias, cross-validation also helps us with avoiding overfitting. By dividing the dataset into a train and validation set, we can concretely check that our model performs well on data seen during training and not.

This project was carried out on a spark 2.3.3, sparklyr 1.2.0., and considering a local Spark cluster environment.

<br>

### Table of Contents   (  [  Link to R codes notebook ]( https://www.arqmain.net/Researches/Researchs/BigData/Sparklyr_KFold/KFold_CV_MLClassifiers_Sparklyr.html))

### WHAT IS IT ALL ABOUT?
### DATA SOURCE
### LOADING AND PREPARING THE DATA
#### LOADING THE DATA
#### PREPARING THE DATA
##### Changing characters to numbers
##### How about the distribution of NA’s?
##### Bucketizing

### MODELING BY K FOLD CROSS VALIDATION (CV)
#### K FOLD CV USING USER-DEFINED FUNCTIONS
##### Getting K Fold CV for three models
######  Model: Random Forest (RForest)
######  Model: Decision Tree (DTree)
######  Model: Logistic Regression (RLogistic)
##### Result's Visualization
#### K FOLD CV USING BUILT INTO SPARK / SPARKLYR FUNCTIONS
##### Getting K Fold CV with almost not tuning
######  CV process:
######  Predict new values on another dataframe:Predict new values on another dataframe:
#### K FOLD CV USING BUILT INTO SPARK / SPARKLYR FUNCTIONS
##### Getting K Fold CV with more explicit tuning
######  CV process:
######  Predict new values on another dataframe:Predict new values on another dataframe:

### FINAL WORDS

<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Visualizations and Applied Statistics / May 11, 2020<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>

