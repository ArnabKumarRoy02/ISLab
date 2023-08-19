# Numpy Basics

NumPy is a Python library.
NumPy is used for working with arrays.
NumPy is short for "Numerical Python"

## np.array
NumPy is used to work with arrays. The array object in NumPy is called ndarray. We can create a NumPy ndarray object by using the array() function.

type(): This built-in Python function tells us the type of the object passed to it. Like in above code it shows that arr is numpy.ndarray type.

```shell
nums = np.array([1, 2, 3, 4, 5])
```

## np.arange
The arange function is used to generate a numeric sequence wherein there are primarily 2 parameters (start, end). It generates numbers from start till end - 1 i.e., say (0, 5) - It generates 0, 1, 2, 3, 4.

If there are 3 parameters say (1, 7, 2) it generates the numbers between 1 and 7 but with a difference of 2 i.e., 1, 3, 5.

## np.zeros
The zeros function is used to create an array of zeros.

```shell
nums = np.zeros(5)
```
This creates an zero array of size 5.

## np.ones
The ones function is used to create an array of ones. This is similar to that of zeros.

## np.linspace
Return evenly spaced numbers over a specified interval. Returns num evenly spaced samples, calculated over the interval [start, stop].

## np.eye
The eye tool returns a 2-D array with 1’s as the diagonal and 0’s elsewhere. The diagonal can be main, upper, or lower depending on the optional parameter k. A positive k is for the upper diagonal, a negative k is for the lower, and a 0 k (default) is for the main diagonal.

## np.random
The random library in Python uses Binomial distribution whereas the np.random library uses Gaussian distribution. The np.random library generates more random numbers in comparison to just the random library.

```shell
random = np.random.rand(2, 3)
random = np.random.randint(50, 100, 5)
```

## np.reshape

```shell
nums = np.arange(1, 17)
nums2 = nums.reshape(4, 4)
```

## np.min
Returns the minumum number in an numpy array.

## np.max
Returns the maximum number in an numpy array.

## np.argmin
Returns the argument or index of the minimum number of the numpy array.

## np.argmax
Returns the argument or index of the maximum number of the numpy array.
