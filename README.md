# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:

### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.

## PROGRAM:
```
'''
Developed by: PYNAM VINODH
Register No: 212223240131
'''
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('GTA.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:

Program file:
![Screenshot 2023-12-24 132607](https://github.com/Jeshwanthkumarpayyavula/Read-from-CSV/assets/145742402/5cc20fe1-52b7-4b8e-b581-e4c9cc975441)

Output:
![Screenshot 2023-12-24 132810](https://github.com/Jeshwanthkumarpayyavula/Read-from-CSV/assets/145742402/774ebf32-b7bb-40f6-b7aa-17ac5d8dfd0b)

## RESULT:
Thus python program for reading content from CSV file is successful.
