# Pandas Basics

Pandas is a Python library. Pandas is used to analyze data.

## pd.Series

```shell
S = pd.Series([3, -5, 7, 4], index=['a', 'b', 'c', 'd'])
```
This index 3 with `a`, -5 with `b`, 7 with `c` and 4 with `d`.

## pd.DataFrame

A Pandas DataFrame is a 2 dimensional data structure, like a 2 dimensional array, or a table with rows and columns.

```shell
data = [['Tagore', 100], ['Ray', 70], ['Dutta', 50]]
Df = pd.DataFrame(data, columns=['Name', 'Price'])
```

## pd.read_csv

This function is used to read a csv file that is locally stored.

```shell
df = pd.read_csv('data.csv')
```

## pd.to_csv

This function is used to convert a current dataframe to a csv file.

```shell
df.to_csv('abcd.csv')
```

## df.sort_index

This function is used to sort the data in according to the index of the values.

## df.sort_values(para)

This function is used to sort the data in according to the parameter

## df.iloc

This function is used to selected a single value by row and cols index.

```shell
df = df.iloc[[r], [c]]
```

## df.ix

This functions selects a single row with all columns.

## df.shape

This function returns the shape of the dataframe.

## df.index

## df.columns

## df.info

The DataFrames object has a method called info(), that gives you more information about the data set.

## df.count

Returns the count of non-NA cells for each column or row.

## df.sum

Returns the sum of values.

## df.cumsum

Returns the cummalative sum of the values.

## df.min / df.max

Returns the min / max value of the dataset.

## df.idxmin

The idxmin() method returns a Series with the index of the minimum value for each column.

## df.describe

Returns the summary of the dataframe.

## df.mean

Returns the mean value from the dataframe.

## df.median

Returns the median value from the dataframe.
