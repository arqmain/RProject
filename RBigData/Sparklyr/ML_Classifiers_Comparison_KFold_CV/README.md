# Big Data: ML Classifiers Comparison in Apache Spark using K-Fold CV and Sparklyr

<br>

This project is about a way to compare the machine learning models that have been generated through a K-Fold CV procedure with Apache Spark using the Sparklyr R package.

We all know that the cross-validation function built into Spark / Sparklyr (in-built cross-validation function) does not return performance metrics for each fold yet. Therefore, it does not allow to be able to develop comparison methods that use the information generated in each step of the implicit cross-validation process.

However, it is possible to build procedures, such as the one used in this project, that allows us to compare the final models obtained based on their behavior using the total database that has generated them through the K-Fold CV process.

This project was carried out on a Spark 2.3.3, Sparklyr 1.2.0., and considering a local Spark cluster environment.

<br>

### Table of Contents   (  [  Link to R codes notebook ]( https://www.arqmain.net/Researches/Researchs/BigData/ML_Classifiers_Comparison_KFold_CV/ML_Classifiers_Comparison_KFold_CV.html))

### WHAT IS IT ALL ABOUT?
### DATA SOURCE
### LOADING AND PREPARING THE DATA
#### LOADING THE DATA
#### PREPARING THE DATA
##### Changing characters to numbers
##### How about the distribution of NA’s?
##### Bucketizing

### MODELING BY K FOLD CV USING BUILT INTO SPARK / SPARKLYR FUNCTIONS
#### GENERALITIES
#### K FOLD CV MODELING
##### RANDOM FOREST MODEL
##### DECISION TREE MODEL
##### LOGISTIC REGRESION MODEL
#### COMPARE RESULTS AND SELECT BEST MODEL
##### COMPARE RESULTS
##### MODEL SELECTION

### FINAL WORDS
<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Visualizations and Applied Statistics / May 16, 2020<br>
>Email: <arqmain2010@gmail.com> <br>
>Url: [http://www.arqmain.net]   /   GitHub: [https://github.com/arqmain]</i>
