# PROJECT - Chicago Car Crashes
_____________________________________________________________________________________________________________

![Trip-Neighborhoods-HERO-2048x1302](https://user-images.githubusercontent.com/78184393/208225930-5e04d211-e896-4ede-b0a3-74dd803726ac.jpg)


## DATASET DESCRIPTION
______________________________________________________________________________________________________________
Using the data from "Chicago Car Crash Dataset" which has  more than 569700 records. The dataset has details of date and time of accident occurred, location and cause of accidents and so. This dataset can be available from chicago government webbsite. This dataset consist of lot of missing values.
- https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if/data

This analysis contains the visualization in the form of various graphs and python libraries which are used in this notebook are Numpy, Pandas, Matplotlib, Seaborn. Pandas for data analysis numpy for scientific computation matplotlib for basic plotting seaborn for advanced plotting sci-kit learn for modeling and evaluations.

## PROBLEM STATEMENT
________________________________________________________________________________________________________________
Building a model to predict the severity of a traffic crashes based on Chicago Police Department crash dataset

## STEPS PERFORMED IN THIS ANALYSIS
_________________________________________________________________________________________________________________
- Data inspection and checking the missing values.
- Splitting data into train and test data.
- Creation of pipeline.
- Checking the performance of Logistic regression, decision tree and Random Forest.
- Checking whether the performance has been improved or not.
- Coming to a conclusion for the best performance.
- We'll focus on preprocessing our data.

Important steps such as identifying and handling null values in the columns. Converted object type feature to int or float type using pandas fuctions. Merged and capped the columns to reduce outliers. Dropped the column which are inconclusive. Transformed categorial variables by using one-hot encoding or "dummy variables".

## CONCLUSION
________________________________________________________________________________________________________________
We are able to get an accuracy score of around 0.8290781329331086 final model shows that certain columns have more of an effect on the severity of a car accident than others. Demonstrated how different classification models work and how we can compare models using roc_auc score metric. I used Random Forest classifier due to its high score among the all models used.
Noticed increased number of the accidents is in the month closer to  October. Noticed increased number of accidents in the rush hour. Most accidents occurred in a clear weather condition. Accidents aremore likely to occur in summer season. Most accidents happened in a dry road condition. Most severe and non severe accident damage cost is more than $1500.

## NEXT STEPS
_______________________________________________________________________________________________________________
Looking to explore the dataset a little more to reduce the number of crashes.

## POWERPOINT PRESENTATION LINK
________________________________________________________________________________________________________________
- https://github.com/DATA-606-FALL-2022/data606_Vivek/blob/main/MYPPT1.pptx
