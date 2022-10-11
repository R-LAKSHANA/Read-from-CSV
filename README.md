# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the contents in the CSV file using read_csv().
### Step 3:
Use head() to get the contents from the starting of the file. 
### Step 4:
Use tail() to get the contents from the end of file.
### Step 5:
Use len() to get the number of rows and columns.

## PROGRAM:
```python
'''
Program for reading content from a CSV file.
Developed by: R LAKSHANA
RegisterNumber: 22004909
'''
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```

## OUTPUT:

![output](/Output.png)

## RESULT:
Thus the program to read the content from CSV file is written and verified using python
programming.