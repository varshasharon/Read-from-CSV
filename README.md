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
![csv1](https://user-images.githubusercontent.com/98278161/214897451-56e962c8-ec23-4bd4-9560-deb256a7afe5.jpeg)
![csv2](https://user-images.githubusercontent.com/98278161/214897517-334dd080-5e48-4dba-aacb-f8635a6cfdae.jpeg)

## RESULT:
Thus, the program is run successfully.
