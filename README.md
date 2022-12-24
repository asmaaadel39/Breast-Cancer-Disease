# Breast Cancer-Disease
![breast-cancer-awareness-month-background-cartoon-illustration-with-ribbon-pink-and-woman-for-disease-prevention-campaign-or-healthcare-vector](https://user-images.githubusercontent.com/114780478/201524163-4b8b53b0-a19a-45d1-8183-ba00eda4688f.jpg)

The Aglorithms, That's am going to cover in this project, I have studied from **Predictive Analytics and Data Minig Book by: Vijay Kotu. 


**1.1 WHAT DATA MINING IS**

Data mining, in simple terms, is finding useful patterns in the data. Being a
buzzword, there are a wide variety of definitions and criteria for data mining.
Data mining is also referred to as knowledge discovery, machine learning, and
predictive analytics.


**1.2 WHAT DATA MINING IS NOT**

While data mining covers a wide set of techniques, applications, and disciplines,
not all analytical and discovery methods are considered data mining
processes. Data mining is usually applied, though not limited to, large data
sets. Data mining also goes through a defined process of exploration, preprocessing,
modeling, evaluation, and knowledge extraction. Here are some commonly
used data discovery techniques that are not considered data mining,
even if they operate on large data sets:
Descriptive statistics: Computing mean, standard deviation, and other
descriptive statistics quantify the aggregate structure of a data set. This is
essential information to understand any data set, but calculating these
statistics is not considered a data mining technique. However, they are
used in the exploration stage of the data mining process.
Exploratory visualization: The process of expressing data in visual
coordinates enables users to find patterns and relationships in the data
and comprehend large data sets. Similar to descriptive statistics, they are
integral in the preprocessing and postprocessing steps in data mining.
Also Dimensional slicing, and Hypothesis testing.


**Types of Data Mining**


![types of data minig](https://user-images.githubusercontent.com/114780478/201524594-41e1853f-1036-4ee3-89e4-ddb682d19b92.jpg)

I will try to explain each algorthim in my repo while am applying it to my project.

**Project Case:**

Predict whether the cancer is benign or malignant using some classification Algorithms.
This Project will contain two phases:

**Phase one**

I will use RapidMiner 

**RapidMiner** is  a powerful data mining tool that enables everything from data mining to model deployment, and model operations, an end-to-end data science platform offers all of the data preparation and machine learning capabilities needed to drive real impact across your organization.

**Phase Two**

I will use Python.

**About Dataset**

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

**Attribute Information:**

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

**Phase 1**
I started with the Data Exploration:

I prepared the data using Python.

...... Check Missing Values......

...... Duplicates Values........

...... Summary Statistics.......


...... Find outliers............

...... Some Visualization.......

Then export the data using ( df.to_csv('mycsvfile.csv',index=False)  )

To Import it in RapidMiner.

**Classification Algorithms**

 
 1-Decision Tree
 
 2-Rule Induction ( will be coverd using Rapid Miner only)
 
 3-Support Vector Machine
 
 4-Naive Bayes
 
 5-Artificial Neural Network
 
 All these algorithms will be covered in both python and rapied miner, To make a comparison between the results ( Accuracy , Computational effort)



