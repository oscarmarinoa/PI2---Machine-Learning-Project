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

* Train.csv: Table containing information regarding properties in Colombia, their prices, locations, amenities among other characteristics. This is the data to train the model for defining the cheap or expensive tag.
* Test.csv: Table containing information for properties in Colombia, for which the definition of expensive or cheap adjective will be predicted.

## 1. Data extraction and load of datasets:

In this first stage a function was created to read different files extensions and return an appropriate Dataframe. The user has to copy the relative path of the file in the designated variable and execute the script.

**Note:** It is important to note that the function can read files with similar characteristics to the files used for the current project.

## 2. Data cleansing and transformation with python:

For the second stage a data exploration process was caried out, identifying the structure of the data, its properties and missing values.

Another function was developed to clean and normalize the data from the Precio_semana files. The function takes the returned Dataframe from the previous step and execute a transformation process in which null values are transformed to 0 to preserve the integrity of the data, the repeated values are deleted and values with typos are corrected and transformed to the proper structure.

## 3. Machine learning model and hyperparameters:

A local database is created using MySQL server to storage the corrected dataframes.

## 4. Calculation of accuracy parameters.

## 5. Hyperparameters update: 



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

## Contact

Oscar Mario Mariño Arias: oscarmarinoa@gmail.com 

[LinkedIn](https://www.linkedin.com/in/oscar-mariño-arias-774098112/)
