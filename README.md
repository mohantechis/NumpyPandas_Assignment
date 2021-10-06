
#Numpy Pandas Assignements
1) Generate an array of zeroes using inbuilt numpy function.
In [ ]:

2) Run the given code and find the dot product of both arrays.
In [41]:
import numpy as np
a = np.random.randint(2,10, (3,4))
b = np.random.randint(2,10, (4,3))
print(a)
print(b)
[[3 6 4 9]
 [7 4 6 7]
 [5 6 8 6]]
[[2 7 7]
 [4 3 7]
 [2 5 3]
 [5 3 6]]
In [42]:
a.dot(b)
Out[42]:
array([[ 83,  86, 129],
       [ 77, 112, 137],
       [ 80, 111, 137]])
In [43]:
#Your code here
3)Read the csv file provided using pandas and display the first 5 entries
In [ ]:

4)Describe the data with all features.
In [ ]:

5)Find the total count of missing values for each feature.
In [ ]:

6)Display all the unique values from the 'DESCRIPTION’ column.
In [ ]:

7)Create a grouped table usin 'DESCRIPTION' as the grouping columns with the means of all the other columns.
In [ ]:

8)Generate a random sample of 10 rows from the data.
In [ ]:

9)Add a Feature called 'New_feature' to the new Dataset and Add Random float Values in between 0 and 1 using Numpy.
In [ ]:

10) Replace zero value of column 'OBJECTID' with mean value permanently.
In [ ]:
