# Inverse-of-matrix

## AIM:
To write a python program to find the inverse of a matrix.
## ALGORITHM:
### Step 1:
Import Numpy module as np.


### Step 2:
Create empty lists.
### Step 3:
Get input from the user for number of rows and columns.
### Step 4:
Use nested lists to append list.
### Step 5:
Print the inverse of the array using np.linalg.inv

## PROGRAM:
```python
To write a python program to find the inverse of a matrix.
Developed by:Harini V
Register Number: 22004214

import numpy as np
l1, l2 = [],[]
r,c= int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)   
value1= np.array(l2)
inverse = np.linalg.inv(value1)
print(inverse)
```

## OUTPUT:
![output](/output.png)

## RESULT:
Thus a program is written to find the inverse of the matrix.