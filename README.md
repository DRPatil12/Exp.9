# EXP 9: Tools for EDA – Study of NumPy Library

Name: Dhruv Patil

PRN: 25070123146

# AIM

  To study and implement the basic functionalities of the NumPy library in Python, including array creation, determining dimensions and shape,
  checking data types, performing numerical operations, and using built-in mathematical functions for Exploratory Data Analysis (EDA).

## THEORY

## NumPy (Numerical Python) is a fundamental Python library used for numerical computations. It provides support for:

 - Multidimensional arrays (ndarray)

 - Mathematical and statistical operations

 - Broadcasting

 - Linear algebra operations

## Why NumPy?

 - It is faster than Python lists because it is implemented in C.

 - It requires less memory.

 - It is widely used for numerical computations.

 - It serves as the base library for data analysis libraries like Pandas.

## Key Concepts Covered:

### Array Creation

 - np.array() creates 1D and 2D arrays.

 - List of lists can represent matrices.

### Array Properties

 - ndim → Returns dimension of array.

 - shape → Returns rows and columns.

 - dtype → Returns data type of elements.

## Built-in Functions:

    np.zeros() → Creates array filled with zeros.

    np.ones() → Creates array filled with ones.

    np.eye() → Identity matrix.

    np.arange() → Array with evenly spaced values.

    np.linspace() → Equal spaced numbers between a range.

    np.mean() → Mean value.

    np.median() → Median value.

    np.max() → Maximum value.

    np.min() → Minimum value.

    np.sum() → Sum of elements.

## Arithmetic Operations:

 - Addition, multiplication with scalar values.

 - Element-wise operations.

 - NumPy arrays support vectorized operations, making computations efficient and fast.
  
# Algorithm:

## 1. Declaration of NumPy & Array Creation:

    Start the program.

    Import NumPy library as np.

    Create a 1D array a using np.array() with elements [1,10,20,30,40,50,500].

    Create a 2D array b using np.array() with list of lists [[1,2,3],[4,5,6]].

    Print array a.

    Print array b.

    Stop.

## 2. Find Dimension of Array:

    Start the program.

    Use the previously created arrays a and b.

    Use a.ndim to find the dimension of array a.

    Use b.ndim to find the dimension of array b.

    Print both dimensions.

    Stop.

## 3. Print Shape (Rows and Columns):

    Start the program.

    Use arrays a and b.

    Use a.shape to determine the size of array a.

    Use b.shape to determine rows and columns of array b.

    Print both shapes.

    Stop.

## 4. Print Data Type of Array:

    Start the program.

    Use arrays a and b.

    Use a.dtype to check datatype of array a.

    Use b.dtype to check datatype of array b.

    Print the datatypes.

    Stop.

## 5. Use of In-Built NumPy Functions:

    Start the program.

    Create a zero matrix of size (2,3) using np.zeros().

    Create a ones matrix of size (2,3) using np.ones().

    Create a 3×3 identity matrix using np.eye().

    Create an array from 1 to 10 with step 2 using np.arange().

    Create an equally spaced array between 0 and 1 with 4 values using np.linspace().

    Calculate mean of array a using np.mean().

    Calculate median of array a using np.median().

    Find maximum value using np.max().

    Find minimum value using np.min().

    Find sum using np.sum().

    Print all results.

    Stop.

## 6. Addition and Multiplication with a Number:

    Start the program.

    Use existing arrays a and b.

    Add scalar value 5 to array a using a + 5.

    Multiply array b by scalar value 2 using b * 2.

    Print the modified arrays.

    Stop.

# CONCLUSION

In this experiment, we successfully studied the basics of the NumPy library. We learned how to:

-Create 1D and 2D arrays

-Determine dimensions, shape, and datatype

-Use built-in mathematical and statistical functions

-Perform arithmetic operations on arrays

-NumPy is an efficient and powerful library for numerical computation and forms the foundation for data analysis and machine learning libraries. It plays an important role in Exploratory Data Analysis (EDA).

-If you want, I can also format this in a practical journal format (ready to print).
