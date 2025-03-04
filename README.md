to use ipykernel and install
conda install -p c:\Users\PAVANS~1\Desktop\eda\venv ipykernel --update-deps --force-reinstall

when we get this error while reading .csv file (utf-8' codec can't decode byte 0xed in position 7044: invalid continuation byte)
use- encoder {df=pd.read_csv('zomato.csv',encoding='latin-1')}



count()-gives the total no of elements in a column
value_counts()-gives quantity of each category in a column



percentage formats

" %1.2f%% "
     after . write 2 decimal values


.reset_index()-resets the index of a DataFrame back to the default numerical sequence (starting from 0), essentially replacing any existing custom index with a simple, sequential integer index


.size()-In Python, .size() is used to find the number of elements in an object, and its behavior depends on the type of object it's applied to.
import numpy as np
arr = np.array([[1, 2, 3], [4, 5, 6]])
print(arr.size) # Output: 6


        For NumPy arrays, .size returns the total number of elements in the array. This is equivalent to the product of the dimensions in the array's shape.
        In Pandas, .size returns the number of elements. For a DataFrame, it's the number of rows multiplied by the number of columns. For a Series, it's the number of elements in the Series.
        import pandas as pd


df = pd.DataFrame({'A': [1, 2], 'B': [3, 4], 'C': [5, 6]})
print(df.size) # Output: 6

s = pd.Series([10, 20, 30, 40])
print(s.size) # Output: 4