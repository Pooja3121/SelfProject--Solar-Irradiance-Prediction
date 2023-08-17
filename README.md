Solar Irradiance Prediction

Data Description <br />
These datasets are meteorological data from the HI-SEAS weather station from four months (September through December 2016) between Mission IV and Mission V <br />
For each dataset, the fields are: <br />
A row number (1-n) is useful in sorting this export's results The UNIX time_t date (seconds since Jan 1, 1970). Useful in sorting this export's results with other export's results The date in yyyy-mm-dd format The local time of day in hh:mm:ss 24-hour format The numeric data, if any (may be an empty string) The text data, if any (may be an empty string)<br />
The units of each dataset are:<br />
Solar radiation: watts per meter^2<br />
Temperature: degrees Fahrenheit<br />
Humidity: percent<br />
Barometric pressure: Hg <br />
Wind direction: degrees <br />
Wind speed: miles per hour <br />
Sunrise/sunset: Hawaii time <br />


What I have done on the Project: <br />
Importing Libraries <br />
Loading Data <br />
Data Wrangling <br />
Feature Selection using Correlation Matrix <br />
Feature Selection using SelectKBest Method <br />
Feature Selection using Extra Tree Classifier <br />
Feature Engineering with BoxCox, Log, Min-Max and Standard transformation <br />
Preparing data - Standardisation and Splitting <br />
Prediction with XGBoost <br />
Using MultiLayer Perceptron for prediction
