# Task10-NumPy-Indexing-and-Slicing
Objective
Learn how to access numerical data efficiently in one-dimensional and two-dimensional arrays.
Tools Used
Python
NumPy
Jupyter Notebook
Topics Covered
One-dimensional array indexing
Two-dimensional array indexing using array[row, column]
Positive and negative indexing
Array slicing and selecting ranges
Example
import numpy as np

arr = np.array([10, 20, 30, 40, 50])

print(arr[0])      # First element
print(arr[-1])     # Last element
print(arr[1:4])    # Elements at index 1 to 3
Sample Output
10
50
[20 30 40]
Key Learning
Python indexing starts at 0, and the ending index in a slice is excluded. NumPy indexing and slicing make it easy to retrieve specific data from arrays.
