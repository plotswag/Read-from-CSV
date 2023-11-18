# Read-from-CSV

## AIM:

## ALGORITHM:
### Step 1:
Import pandas module as pd.

### Step 2:
Using pd.read_csv() method read the CSV file.

### Step 3:
Using df.head() print the first 10 rows of the CSV file.

### Step 4:
Using df.tail() print the last 5 of the CSV file.
### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
import pandas as pd
f = pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row:', len(f.axes[0]))
print('Col:', len(f.axes[1]))
```
## OUTPUT:
![image](https://github.com/plotswag/Read-from-CSV/assets/145822344/b396f3f2-1668-4b9a-af3c-8a790f83af46)

## RESULT:
Thus the program executed successfully.
