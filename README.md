# Data wrangling

## This is a practise of python
1.Create a DataFrame named df with 6 nrows with the following columns:

2.A: random floating point value
B: randomly assigned categorical values from ["test", "train"]
C: random integer values, constructed from an numpy.array
D: random integer values, constructed from a Series
E: monthly dates "2021-01-01", "2021-02-01", "2021-03-01" ...
Convert numeric columns into a numpy.matrix and compute the row sums.

3.Sort df by column C.

4.Filter df for entries for which B has value train and C has values greater than 0.

5.Change the value in the 4th column and 2nd row to 10.

6.Create a column F where half the values are NaN.

7.Deal with missing values in two different ways:

8.remove entries with missing data
fill missing values with 0
Convert column A into a cumulative sum.

9.Subtract column A from column B.

10.Plot the numeric columns as a line plot, ensuring that the plot has proper labels.

11.Compute the mean values of each column for groups train and test.

12.Convert the following DataFrame from a into b (long to wide). Additionally, convert from b into a (wide to long).

a = pd.DataFrame(
    {"value": [1, 2, 3, 4, 5, 6], "group": ["a", "a", "a", "b", "b", "b"]}
)

b = pd.DataFrame(
    {"a": [1, 2, 3], "b": [4, 5, 6]}
)
