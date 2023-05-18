# Glass Identification
Creating predictive models on an imbalanced Glass Identification Data set. 
The purpose of this project is to creative predictive models on an imbalanced dataset, and recreate them after Oversampling the data with SMOTE.
Synthetic Minority Oversampling Technique ( SMOTE ), is a Oversamling technique that creates synthetic data for minor classes.

## Data Source
https://archive.ics.uci.edu/ml/datasets/Glass+Identification

## Data Information
This a Glass Identification Data Set taken from the UCI Machine Learning Repository. The motivation behind the study of classification for types of class was to aid in Criminal Investigation. 

## Attribute Information:

1. Id number: 1 to 214
2. RI: refractive index
3. Na: Sodium (unit measurement: weight percent in corresponding oxide, as are attributes 4-10)
4. Mg: Magnesium
5. Al: Aluminum
6. Si: Silicon
7. K: Potassium
8. Ca: Calcium
9. Ba: Barium
10. Fe: Iron
11. Type of glass: (class attribute)
    1) building_windows_float_processed
    2) building_windows_non_float_processed
    3) vehicle_windows_float_processed
    4) vehicle_windows_non_float_processed (none in this database)
    5) containers
    6) tableware
    7) headlamps

## Outline

1) Importing and Preparing Data
*  Remove unneeded columns
*  Add column names

2) Data Visualization
* Univariative Plots ( Histogram, Box Plot)
* Multivariative Plots ( Pair Plot, Correlation Plot ) 
3) Creating Train and Test Data
* Normalizaion of Data
4) Creating Predictive Models
* K-Nearest Neighbors
* Support Vector Classifier
* Random Forest Classifier
* Decision Tree Classifier
5) Creating SMOTE Train and Test Data
* Using SMOTE for Oversampling, and recreating Train and Test Data.
6) Creating SMOTE Predictive Models
* Recreating Models
7) Choosing the best Model
* Using F1 SCORE and Cross Validation Means to choose the best model

## Best Model
The best performing model was Random Forest Classifier for both pre and post SMOTE models. RFC not only had a high F1 Score, but also a high Cross Validation Mean to support it.
