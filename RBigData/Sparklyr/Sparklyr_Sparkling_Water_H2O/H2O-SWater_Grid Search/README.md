# Big Data: K-Fold CV ML Classifiers with Spark, Sparklyr, and H2O-Sparkling Water

<br>

H2O is a product created by the H2O.ai company to combine the main algorithms of machine learning and statistical learning with Big Data. Thanks to its way of compressing and storing data, H2O can work with millions of records in a single computer (it uses all its cores) or in a cluster of many computers. Internally, H2O is written in Java and follows the Key / Value paradigm for storing data and Map / Reduce for its algorithms. Thanks to its APIs, it is possible to access all its functions from R, Python, or Scala, as well as through a web interface called Flow.

Although H2O's main advantage over other tools is its scalability, its algorithms are equally useful when working with a small volume of data. H2O is an open source, distributed machine learning platform for Everyone. H2O is an alternative open-source cross-platform for machine learning that supports the most widely used statistical & machine learning algorithms including gradient boosted machines, generalized linear models, deep learning and more.

This present work is about an application and practical exposition of how to apply two classic Grid Search methods for tunning four (Glm, RandomForest, Gbm, Deeplearning) of the most frequently used machine learning models for classification, by using Sparklyr, rsparkling and H2O-Sparkling Water. The main results obtained are presented here, providing a clear guideline that identifies the classic steps in the modeling process, possible to adapt to any other equivalent database. The key functions and scripts used are proporcionated, allowing the reader to consult the appropriate bibliography and tutorial examples clearly and directly.

<br>

### Table of Contents   (  [  Link to R codes notebook ]( https://github.com/arqmain/RProject/blob/master/RBigData/Sparklyr/Sparklyr_Sparkling_Water_H2O/H2O-SWater_Grid%20Search/MLearning_Classifiers_Sparklyr_H2O-SWater_Grid%20Search.pdf))

### WHAT IS IT ALL ABOUT?
### DATA SOURCE
### LOADING THE DATA
### READJUSTMENT DATASET
#### GETTING DATASET INTO H2O FORMAT
#### TRANSFORM CATEGORICAL FEATURES INTO FACTORS
#### EXPLORING THE DATA
### GETTING THE TRAIN AND TEST DATASET
#### GETTING TRAIN AND TEST DATASETS
### GRID SEARCH GENERALITIES
#### INTRODUCTION
#### CARTESIAN AND RANDOM GRID SEARCHING OF HYPERPARAMETERS
### GRID SEARCH MODELING
#### MODEL: LOGISTIC REGRESSION (LR_model)
#### MODEL: RANDOM FOREST (RForest_model)
#### MODEL: GRADIENT BOOSTING MACHINE (GBM_model)
#### MODEL: DEEP LEARNING - NEURAL NETWORKS (DL_model)
### SELECT BEST MODEL AND MAKE PREDICTIONS
#### SELECT BEST MODEL
#### BEST MODELS BY TRAIN/TEST METHOD
#### BEST MODELS BY KFOLD METHOD
### FINAL WORDS


<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Visualizations and Applied Statistics / August 30, 2020<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
