# Denver-Precipitation-Prediction
Project Authors: Ryne Smith and Ryan James. (All code in this repository was written by Ryne Smith).

The pdf report describes the project in detail, however the summary is that we used a random forest regressor model (from Scikit-learn) to predict precipitation, initially using the features for year, month, day, latitude, longitude, and elevation from our raw daily precipitation reports. These reports came from weather stations around the Denver metro, sourced from https://www.ncdc.noaa.gov/cdo-web/. After performing some initial data analysis and cleaning (detailed in the report), we tested every subset of these features and found that using only the data data (year, month, day) performed better than all other subsets. This model performed with a r^2 score of 0.768 so clearly there is improvement that can be made but overall this project was a great application of different data science skills.
