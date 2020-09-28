# Big Data: PCA Application to MLearning Classification with H2O using Spark, Sparklyr, and H2O-Sparkling Water

<br>
H2O is an open source, distributed machine learning platform for Everyone. Although H2O's main advantage over other tools is its scalability, its algorithms are equally useful when working with a small volume of data. H2O is an open source, distributed machine learning platform for Everyone. H2O is an alternative open-source cross-platform for machine learning that supports the most widely used statistical & machine learning algorithms including gradient boosted machines, generalized linear models, deep learning and more.
<br>
Personally, from some time until now I have incorporated H2O as one of my base platforms to use in conjunction with R and Python when having to deal with machine learning in general. H2O and R form a very powerful team that complements each other well and works very harmoniously in most cases whether in a BigData context or not. The same is probably the case with the H2O and Python team, however, I have not yet tested their behavior in such a way that I can issue a relevant opinion in this regard.

This project is about a way to apply principal component analysis (PCA) to get a new transformed orthogonal dataset to be used in a machine learning modeling context by using Spark, Sparklyr, and H2O-Sparkling Water. The main results obtained are presented here, providing a clear guideline that identifies the classic steps in the modeling process, possible to adapt to any other equivalent database. The key sparklyr and and H2O-Sparkling Water functions used are identified, allowing the reader to consult the appropriate bibliography and tutorial examples clearly and directly.


<br>

### Table of Contents   (  [  Link to R codes notebook ]( https://arqmain.000webhostapp.com/Research/BigData/PCA_MLClassifiers_Sparklyr_H2O/PCA_MLClassifiers_Sparklyr_H2O.html))

### WHAT IS IT ALL ABOUT?
### DATA SOURCE
### LOADING THE DATA
### GETTING THE RESCALING DATASETS
#### GETTING DATASET INTO H2O FORMAT
#### GETTING THE TRAIN AND TEST DATASETS
#### RESCALING TRAIN AND TEST DATASETS BY USING PCA

### MACHINE LEARNING MODELS
#### FITTING THE MODELS
##### Method: Train / Test dataset procedure
##### Method: KFold Cross Validation procedure
##### Method: Random Grid Search KFold Cross Validation procedure

### FINAL WORDS

<hr>

><i>Hector Alvaro Rojas<br>
>Data Science, Visualizations and Applied Statistics / September 27, 2020<br>
>Email: <arqmain2010a@gmail.com> <br>
>Url: [http://arqmain.000webhostapp.com/]   /   GitHub: [https://github.com/arqmain]</i>
