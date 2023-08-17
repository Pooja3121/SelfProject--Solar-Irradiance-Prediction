Solar Irradiance Prediction

Data Description
These datasets are meteorological data from the HI-SEAS weather station from four months (September through December 2016) between Mission IV and Mission V.
For each dataset, the fields are:
A row number (1-n) is useful in sorting this export's results The UNIX time_t date (seconds since Jan 1, 1970). Useful in sorting this export's results with other export's results The date in yyyy-mm-dd format The local time of day in hh:mm:ss 24-hour format The numeric data, if any (may be an empty string) The text data, if any (may be an empty string)
The units of each dataset are:
Solar radiation: watts per meter^2
Temperature: degrees Fahrenheit
Humidity: percent
Barometric pressure: Hg
Wind direction: degrees
Wind speed: miles per hour
Sunrise/sunset: Hawaii time


What I have done on the Project:
Importing Libraries
Loading Data
Data Wrangling
Feature Selection using Correlation Matrix
Feature Selection using SelectKBest Method
Feature Selection using Extra Tree Classifier
Feature Engineering with BoxCox, Log, Min-Max and Standard transformation
Preparing data - Standardisation and Splitting
Prediction with XGBoost
Using MultiLayer Perceptron for prediction
