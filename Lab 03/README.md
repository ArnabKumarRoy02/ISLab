# Data Preprocessing

Data preprocessing is the process of preparing raw data for analysis. It involves cleaning, transforming, and integrating data to make it ready for analysis. The goal of data preprocessing is to improve the quality of the data and make it more suitable for the specific data mining task.

## Working with missing data

If the count is too min, we can omit that column, means drop that. Remember, we are creating another refined dataframe with dropped columns, the original dataframe remains unchanged.

## Handling of Categorical Data

We can take care of categorical features by converting them to integers.

There are 2 common ways to do so.
 - Label Encoding
 - One Hot Encoding

## Standardization and Normalization of Dataset

 - ## Standard Scaling

Standard scaling is a scaling technique that makes data scale-free. It involves converting the statistical distribution of the data into the format: mean - 0 (zero); standard deviation - 1. This means that the mean of the attribute becomes zero, and the resultant distribution has a unit standard deviation.

 - ## Normalization

Normalization in Python is the process of rescaling the values of features to a common scale. This is done to make the features more comparable and to improve the performance of machine learning models.

 - ## Min-Max Scaler

Transform features by scaling each feature to a given range. This estimator scales and translates each feature individually such that it is in the given range on the training set, e.g. between zero and one.
