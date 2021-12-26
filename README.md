# Telematics Work Sample

Data science work sampe using telematics data provided by an insurance company.  Data to run the notebook can be made available upon reasonable request.

## Task

The overall task for this particular work sample was to develop a predictive model that determines whether or not a car trip was "interesting" based on the telematics data provided.  The data comes from the users smartphone while they are driving, and it consists of a timeseries of vehicle speed and heading derived from the phones onboard sensors.  In addition to the timeseries data, 15 features about each trip are provided, including whether or not the trip was considered "interesting" by the comapny. The objective was to augument the list of features for each trip by adding two additional features based on the vehicle speed and heading (namely the number of stops and turns), and then, using this new feature set, fit a model to the trip label (whether the trip was "interesting") that can be used to predict the label on a test dataset that is unlabeled.  These predictions on the unlabeled test data were then provided to the company for assesment.

## Implementation
The general format for this work sample is:

1. Data exploration: model features
2. Data exploration: trip data
3. Feature extraction: turns and stops
4. Model development and validation
5. Apply model to make predictions on test data

The write-up assessing the performance of the feature extraction is at the end of section 3, and the write-up assessing the model performance is at the beginning of section 4.

