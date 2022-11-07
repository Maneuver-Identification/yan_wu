# yan_wu
starter code by Yan Wu 

This approach and supplemental code is detailed within the python notebook. Both tasks of sorting the data and classifying it as a certain maneuver are attempted. 
Root directories and directories containing data must be changed by the user. 

For Task 1, basic statistical measures of mean and standard deviation are used to classify the data as 'good' or 'bad'. The accuracy is then tested based on the truth data. No model training is used or required.

For Task 2, a random forest approach is taken to create several collective decision trees based on distinguishing criteria gathered from the parameters of the labeled maneuver truth data. A time series random forest approach is also attempted; the inclusion of time series data in the classification method requires preparation of the data via resampling.
