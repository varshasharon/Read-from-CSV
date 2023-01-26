# Read-from-CSV

## AIM: 
Read from CSV

## ALGORITHM:

### Step 1:
Using the Pandas Library. import pandas as pd.

### Step 2:
Use read_csv() method of pandas library is used to read data from CSV files.

### Step 3:
Print the data in row wise and in column wise.

## PROGRAM:
```python
import pandas as pd
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Row: ',len(f.awes[0]))
print('Col: ',len(f.axes[1]))
```
## OUTPUT:

## RESULT:
