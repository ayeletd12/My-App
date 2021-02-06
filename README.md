# My-App
Shiny (R) application for interactive Exploratory Data Analysis. 

https://ayeletd12.shinyapps.io/EDA_app/

## Gamma version with bugs fixed and new layout is on air! ## 

### Input
Users can upload raw data as CSV format and receive high-level information as data shape, list of features, data types, and variables summary.


## Missing Values 

Visualization - Visualize the proportions of missing values for each feature. Observation of missing values (red) and complete ones (blue).

Treatment 
* Omit all rows with missing values (not recommended in case of many rows containing missing values ).
* Assign a specific value - whether a constant, like 0 or -9999, or a statistic, like mean or median, or users can choose other for specific value. The value assigned to all numeric features while for categorial assign "Missing value" label.


### Feature Selection 
In this section, the users choose the features for the final dataset and the model.

* Target variable - users choose the targer variable, can examine the distribution by univariate plot and examine as factor.
* X Features - users choose the desiered fetures, can examine the distribution, examine transformation as log, square, or root square, to numeric features (will be extended in the future).

  
### Outliers
In this section, the users can deepen the search for outlier and integrity issues in the data:

* Conditional filtering - Applying a condition on a specific variable
* Visual filtering - choose the wanted observations from the graph by double-clicking it.

In both options, a table with the relevant observation will appear below and users can add an examination combination with more filters to the other variables. The user can choose rows from the table by clicking on them and can omit them from the dataset.
 
### Save 
 
The users can download the final dataset

### comming soon
*  Fitting a model
