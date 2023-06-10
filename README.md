# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Start the python.
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.
## PROGRAM:
```
#Program to read data from csv file.
#Devloped By: ROSHINI RK
#Reg no:212222230123
```
```
import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1]))
```
## OUTPUT:

![csvout](https://github.com/roshiniRK/Read-from-CSV/assets/118956165/6c9720d6-38b3-43c9-876b-263123f82208)

## RESULT:
A python program to read data from CSV files has been created successfully.
