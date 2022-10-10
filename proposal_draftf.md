# Draft Proposal for DATA 606:

_______________________________________________________________________________

#### Name: Vivek Pandey
#### Date: 10/10/2022

# Project Title - "CAR CRASHES SEVERITY AND REASON PREDICTION"

___________________________________________________________________________

## OVERVIEW:

Crash data shows information about each traffic crash on city streets within the City of Chicago limits and under the jurisdiction of Chicago Police Department (CPD). Data are shown as is from the electronic crash reporting system (E-Crash) at CPD, excluding any personally identifiable information. Records are added to the data portal when a crash report is finalized or when amendments are made to an existing report in E-Crash. Data from E-Crash are available for some police districts in 2015, but citywide data are not available until September 2017. About half of all crash reports, mostly minor crashes, are self-reported at the police district by the driver(s) involved and the other half are recorded at the scene by the police officer responding to the crash.


## ISSUE OR THE REASON FOR CHOOSING THIS TOPIC:

Many of the crash parameters, including street condition data, weather condition, and posted speed limits, are recorded by the reporting officer based on best available information at the time, but many of these may disagree with posted information or other assessments on road conditions. If any new or updated information on a crash is received, the reporting officer may amend the crash report at a later time. A traffic crash within the city limits for which CPD is not the responding police agency, typically crashes on interstate highways, freeway ramps, and on local roads along the City boundary, are excluded from this dataset.
1. It will help in improving the road conditions for that area.
2. Prediction of accidents. 
3. Reason for most of the accidents and take precautions.
4. Predict the damage cost by accidents in particular area and conditions.


## DATA SOURCE:

Using the data from "Chicago Car Crash Dataset" which as more than 569700 records. The dataset as details of date and time of accident occurred, location and cause of accident and soon.

Link: https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if



Following columns in the dataset are:
- CRASH_RECORD_ID : A unique ID can be used to link to the same crash in the Vehicles and people datasets.
- RD_NO: Chicago Police Department report number.
- CRASH_DATE_EST_I : Crash date estimated by desk officer or reporting party.
- CRASH_DATE : Date and time of crash.
- POSTED_SPEED_LIMIT:Posted speed limit.
- TRAFFIC_CONTROL_DEVICE:Traffic control device present at crash location.
- DEVICE_CONDITION : Condition of traffic control device.
- WEATHER_CONDITION : Weather condition at time of crash.
- LIGHTING_CONDITION: Light condition at time of crasH.
- FIRST_CRASH_TYPE : Type of first collision in crash.
- TRAFFICWAY_TYPE : Trafficway type.
- LANE_CNT : Total number of through lanes in either direction, excluding turn lanes.
- ALIGNMENT : Street alignment at crash location.
- ROADWAY_SURFACE_COND:Road surface condition.
- ROAD_DEFECT : Road defects.
- REPORT_TYPE : Administrative report type (at scene, at desk, amended).
- CRASH_TYPE : A general severity classification for the crash. Can be either Injury and/or Tow
- Due to Crash or No Injury / Drive Away.
- INTERSECTION_RELATED_I:A field observation by the police officer whether an intersection played a role in the crash. Does not represent whether or not the crash occurred within the intersection.
- NOT_RIGHT_OF_WAY_I :Whether the crash begun or first contact was made outside of the public right-of-way.
- HIT_AND_RUN_I : Crash did/did not involve a driver who caused the crash and fled the
scene without exchanging information and/or rendering aid.
- DAMAGE : A field observation of estimated damage.
- DATE_POLICE_NOTIFIED: Calendar date on which police were notified of the crash.
- PRIM_CONTRIBUTORY_CAUSE:The factor which was most significant in causing the crash.
- SEC_CONTRIBUTORY_CAUSE :The factor which was second most significant in causing the crash.
- STREET_NO :Street address number of crash location.
- STREET_DIRECTION :Street address direction (N,E,S,W) of crash location.
- STREET_NAME :Street address name of crash location.
- BEAT_OF_OCCURRENCE :Chicago Police Department Beat ID.
- PHOTOS_TAKEN_I :Whether the Chicago Police Department took photos at the location of the crash.
- STATEMENTS_TAKEN_I :Whether statements were taken from unit(s) involved in crash.
- DOORING_I :Whether crash involved a motor vehicle occupant opening a door into the travel path
of a bicyclist, causing a crash.
- WORK_ZONE_I :Whether the crash occurred in an active work zone.
- WORK_ZONE_TYPE :The type of work zone.
- WORKERS_PRESENT_I :Whether construction workers were present in an active work zone at crash location
- NUM_UNITS :Number of units involved in the crash.
- MOST_SEVERE_INJURY :Most severe injury sustained by any person involved in the crash.
- INJURIES_TOTAL :Total persons sustaining fatal, incapacitating, non-incapacitating, and possible injuries.
- INJURIES_FATAL :Total persons sustaining fatal injuries in the crash.
- INJURIES_INCAPACITATING:Total persons sustaining incapacitating/serious injuries in the crash. - INJURIES_NON_INCAPACITATING:Total persons sustaining non-incapacitating injuries in the crash. -INJURIES_REPORTED_NOT_EVIDENT:Total persons sustaining possible injuries in the crash.
- INJURIES_NO_INDICATION:Total persons sustaining no injuries in the crash.
- INJURIES_UNKNOWN :Total persons for whom injuries sustained, if any, are unknown.

- CRASH_HOUR :The hour of the day component of CRASH_DATE.

- CRASH_DAY_OF_WEEK :The day of the week component of CRASH_DATE. Sunday=1
- CRASH_MONTH :The month component of CRASH_DATE.
- LATITUDE :The latitude of the crash location.
- LONGITUDE :The longitude of the crash location.
- LOCATION :The crash location.

## STEPS PERFORMED IN THIS ANALYSIS
- Data inspection and checking the missing values.
- Splitting data into train and test data.
- Creation of pipeline.
- Checking the performance of Logistic regression, decision tree, and Random Forest.
- Checking whether the performance has been improved or not.
- Coming to a conclusion for the best performance.
- we'll focus on preprocessing our data.


Important steps such as identifying and handling null values in the columns. Converted object type feature to int or float type using pandas functions. Merged and capped the values of columns to reduce the outliers. Dropped the column which are inconclusive. Transformed categorical variables by using one-hot encoding or "dummy variables".

## Setting Up Our Data
The modules that are imported to process the data and build the models are

- pandas for data analysis
- numpy for scientific computation
- matplotlib for basic plotting
-  seaborn for advanced plotting
- sci-kit learn for modeling & evaluations

## Scrub the Data
In this stage, we'll focus on preprocessing our data.

- Important steps such as identifying and handling null values in the columns.
- Converted object type feature to int or float type using pandas functions.
- Merged and capped the values of columns to reduce the outliers.
- Dropped the column which are inconclusive.
- Transformed categorical variables by using one-hot encoding or "dummy variables".

## MODELS TO USE:

#### Logistic Regression
Logistic Regression is used when the dependent variable is binary in nature. It is a powerful statistical tool which can be used to predict the effect of the factors that are related to the crashes.

#### Decision Tree Classifier

#### Random Forest Classifier
Random Forest Trees are based on a number of prediction trees that are
less tolerant to noise andutilize random selection of features in splitting the trees.



## Outcomes planning to achieve:

- In the narrow sense, the goal of forecasting is to produce better forecasts. 

- Final models to show that certain columns have more of an effect on the severity of a car accident than others.

- To demonstrate how different classification models work and how we can compare models using the roc_auc score metric.

- Planning to use Random Forest classifier due to its high score among the all models.



```python

```
