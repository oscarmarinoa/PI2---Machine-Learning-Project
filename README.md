# PI2---Machine-Learning-Project
Machine learning project focused on defining if some properties in Colombia are expensive or cheap.
This project corresponds to the second individual project of the Data Science career of 
Henry cohort 04 (DS04)
## Procedure

1. Data extraction and load of datasets.
2. Data cleansing and transformation with python.
3. Machine learning model and hyperparameters. definition (sklearn).
4. Calculation of accuracy parameters.
5. Hyperparameters update.

## Dataset

The dataset for this project is formed by .

* Train.csv: Table containing information regarding to several properties in Colombia, their prices, locations, amenities among other characteristics. This is the data to train the machine learning model for defining the cheap or expensive tag.
* Test.csv: Table containing information for properties in Colombia, for which the definition of expensive or cheap classification will be predicted.

## 1. Data extraction and load of datasets:

In this first stage the files are openeded as Dataframes using the Pandas Library.

## 2. Data cleansing and transformation with python:

This stage is focused on handling the missing and null values of the data, identifying outliers, normalizing numerical variables, transforming categoral data in suitable information for the ML model and performing some feature engineering.

## 3. Machine learning model and hyperparameters:

After the data is ready to be used, we select the machine learning model based on the problem we are trying to solve and the characteristics of the data we are using.

This step and the following two are try and error stages, where the hyper parameters and machine learning models are continuosly change to improve the results obtained.

## 4. Calculation of accuracy parameters.

In order to review the effectiveness of our model for cataloguing the properties correctly, some metrics are calculated:
* Confussion matrix.
* Accuracy.
* Recall.

In this specific project, the performace of the model will be based on how well it can identify expensive properties using the recall:

--> Formula: Recall=TP/TP+FN

where:
TP: True positive.
FN: False negative.

## 5. Hyperparameters update: 

After the data is ready to be used, we select the machine learning model based on the problem we are trying to solve and the characteristics of the data we are using.
improve the results obtained.


## --> About the repository
You will find the following files:
* script.ipynb: A Jupiter notebook file containing all the cleansing and transformation executed to the train file.
* 
* 
* 

## --> Information to highlight
* [Geopy documentation](https://geopy.readthedocs.io/en/stable/)
* [Regular Expression Operation Module - RE](https://docs.python.org/3/library/re.html)
* [numpy.isnan()](https://numpy.org/doc/stable/reference/generated/numpy.isnan.html)

## --> Lessons learned
* [Geopy documentation](https://geopy.readthedocs.io/en/stable/)
* [Regular Expression Operation Module - RE](https://docs.python.org/3/library/re.html)
* [numpy.isnan()](https://numpy.org/doc/stable/reference/generated/numpy.isnan.html)

## Contact

Oscar Mario Mariño Arias: oscarmarinoa@gmail.com 

[LinkedIn](https://www.linkedin.com/in/oscar-mariño-arias-774098112/)
