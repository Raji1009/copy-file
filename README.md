# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7

## ALGORITHM: 
### Step 1:
Use open function to open the file in which we want to copy from and access it in read mode.

### Step 2: 
Read the file and store in a variable

### Step 3: 
Now create a new file in which we want to paste the content using access mode.

### Step 4:  
Use write function to copy the read file that has been stored in the variable.

### Step 5: 
The content in the original file will be copied in the newfile

### Step 6: 
End the program

## PROGRAM:
```
#program to copy contents from one file to another
# Developed by : Rajalakshmi R
# Reg no : 212223110037

import pandas as pd
df=pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows: ",len(df.axes[0]))
print("Number of columns: ",len(df.axes[1]))

```


### OUTPUT:
![image](https://github.com/Raji1009/copy-file/assets/89059861/0b50ff58-a1e8-461d-95a6-4ab7ab38d9ac)

![image](https://github.com/Raji1009/copy-file/assets/89059861/2a7f6c8a-25a7-492e-bd9f-fce266738722)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
