# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

## Step 1:
 
import numpy as np

## Step 2:

From scipy.linalg import lu

## Step 3 :

Get the inputs

## Step 4:

print the values and end the program

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: thanika sree b
RegisterNumber: 22008978

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: thanika sree b
RegisterNumber: 22008978

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

```

## Output:
![lu decomposition](/lu.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

