# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.
##EQUIPEMENT'S REQUIREMENT:
PC Anaconda - Python 3.7



## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
#Program to read contents from csv file
#Developed by: Kishan Shree B
#Register by:212223100022

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("number of columns:",len(df.axes[1]))

```
## OUTPUT:
![image](https://github.com/KishanShreeB/Read-from-CSV/assets/144870434/9c6ceac4-072d-49da-bfea-ee7e411b4c5d)

## RESULT:
Thus the program is written to read the csv file.
