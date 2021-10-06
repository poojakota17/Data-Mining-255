# Data-Mining-255
Data set : https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data
This is New York's Airbnb Data

### Objective : Clean the data using Open Refine and perform a regression and find the accuracy.

1. First the data is analysed to understand different columns. This would help in understanding relation between columns and how needs to be cleaned and used for prediction.
2. The data is cleaned using OpenRefine. The video link of the cleaning done using openrefine : https://drive.google.com/file/d/19YMhRNyOJEIxJbpgrbjx-JbuP5iGONqS/view?usp=sharing
3. Once the data is cleaned , then the null values in 4 columns: last_review, name and host_name are filled with dummy values. For last_review the latest date is added to the NaN values using python.
4. Once this is done, the neighbourhood column is converted to numerical data.
5. Then the data is divided into training and test data and price column is dropped, because we have to predict the prices.
6. Then the data is scaled and passed to Decision tree Regressor.
7. The metric for regression,R-squared error came out to be 0.403 for training data and 0.037 for testing data

