# Read-from-CSV

## AIM:
To write a program to read a content from a CSV File

## ALGORITHM:
### Step 1: 
Import the Pandas library with the alias 'pd'.
### Step 2:
Use the 'pd.read_csv()' function to read the "nba.csv" file located at "C:/Users/admin/Downloads/nba.csv" into a DataFrame object named 'df'.
### Step 3:
Print the first 10 rows of the DataFrame using the 'head()' method.
### Step 4:
Print the last 5 rows of the DataFrame using the 'tail()' method.
### Step 5: 
Print the number of rows and columns in the DataFrame using the 'len()' function along with the 'axes' attribute.

## PROGRAM:
## PROGRAM TO READ A CONTENT FROM A CSV FILE
## Developed by: V.Divyashree
## Register No: 212223230051
/*
```
import pandas as pd
df = pd.read_csv("C:/Users/admin/Downloads/nba.csv")
print(df.head(10))
print(df.tail())
print("Number of rows:", len(df.axes[0]))
print("Number of columns:", len(df.axes[1]))
```
*/

## OUTPUT:
## Head:
![image](https://github.com/divya280/Read-from-CSV/assets/82276099/4ce0f024-2b08-45b5-b399-dec24b29d2dd)

## Tail:
![image](https://github.com/divya280/Read-from-CSV/assets/82276099/fd824a0e-c8cc-43c1-8384-ded940be47dd)

## No. of rows and columns:
![image](https://github.com/divya280/Read-from-CSV/assets/82276099/742957c3-c62c-4eda-85b8-b11fcfbf8082)


## RESULT:
Thus a program for reading a content from a CSV file is executed successfully.
