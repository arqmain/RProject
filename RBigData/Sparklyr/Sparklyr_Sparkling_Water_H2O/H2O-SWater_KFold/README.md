# Big Data: K-Fold CV ML Classifiers with Spark, Sparklyr, and H2O-Sparkling Water

<br>

H2O is a product created by the H2O.ai company to combine the main algorithms of machine learning and statistical learning with Big Data. Thanks to its way of compressing and storing data, H2O can work with millions of records in a single computer (it uses all its cores) or in a cluster of many computers. Internally, H2O is written in Java and follows the Key / Value paradigm for storing data and Map / Reduce for its algorithms. Thanks to its APIs, it is possible to access all its functions from R, Python, or Scala, as well as through a web interface called Flow.

The rsparkling R package is an extension package for sparklyr that creates an R front-end for the Sparkling Water package from H2O. This provides an interface to H2O’s high performance, distributed machine learning algorithms on Spark, using R. Rsparkling provides functions to access H2O’s distributed machine learning functions via sparklyr.

This present work is about an application of some common supervised ML classifiers using K-Fold CV method in Apache Spark using Sparklyr and H2O-Sparkling Water. The main results obtained are presented here, providing a clear guideline that identifies the classic steps in the modeling process, possible to adapt to any other equivalent database. The key sparklyr functions and scripts used are proportionated, allowing the reader to consult the appropriate bibliography and tutorial examples clearly and directly.

<br>

### Table of Contents   (  [  Link to R codes notebook ]( https://arqmain.000webhostapp.com/Research/BigData/H2O-SWater_CValidation/H2O-SWater_KFold/KFold_CV_MLClassifiers_Sparklyr_H2O.html))

### WHAT IS IT ALL ABOUT?
### DATA SOURCE
### LOADING THE DATA
### FEATURE ENGINEERING
#### BUCKETIZING
#### RE_GROUPING QUALITATIVE FEATURES
#### FACTORS INTO INTEGERS

### READJUSTMENT DATASET INTO H2O FORMAT
#### GETTING DATASET INTO H2O FORMAT
#### TRANSFORM CATEGORICAL FEATURES INTO FACTORS

### MACHINE LEARNING MODELS
#### FITTING THE MODELS
##### Model: Logistic Regression (LR_model)
##### Model: Random Forest (RForest_model)
##### Model: Gradient Boosting Machine (GBM_model)
##### Model: Neural Networks (DL_model)
##### Model: Naive Bayes (NB_model)
#### SELECT BEST MODEL AND MAKE PREDICTIONS
##### Select the Best Model
##### Characterization of the best model
##### Making Predictions

### FINAL WORDS


<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Visualizations and Applied Statistics / June 07, 2020<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://arqmain.000webhostapp.com/]   /   GitHub: [https://github.com/arqmain]</i>
