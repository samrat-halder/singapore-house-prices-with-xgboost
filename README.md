# Singapore-House-Prices-with-XGBoost

We try to predict Resale Flat prices in Singapore using Machine Learning. In this project I used XGBoost. We have various data from the website of Housing and Development Board of Singapore. The data spans over many years starting from 1990. Our goal is to build a model that can predict 2019-20 prices from the historical data.
## Data
Source: HDB's website https://www.hdb.gov.sg/cs/infoweb/homepage 

1. Median Prices by town and flat type (Quarterly published)
2. Number of Resale Applications Registered by Flat Type (Quarterly published)
3. HDB Resale Price Index (Quarterly published)
4. Resale Transaction by Flat Type (based on registered cases) (Annually published) etc.

## Results

For the final prediction task we trained our model on 2014-2018 data to test the model on 2019 - 2020 data.

1. Testset RMSPE 0.0923 (uncalibrated)
2. Average Percentage Error on test set is 7.015 % (uncalibrated)
3. RMSPE on test set after calibration 0.0938
4. Average Percentage Error on test set after calibration 7.121 %
5. Model performance is stable
