# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:  
Import required libraries `numpy` and `scipy.linalg`.  

## Step 2:  
Input the matrix/matrices using `eval(input())`.  

## Step 3:  
Perform LU decomposition using `lu()` or solve equations using `lu_factor()` and `lu_solve()`.  

## Step 4:  
Print the results `L` and `U` matrices or solution `X` matrix.  

## Program:
### Program to find the L and U matrix.
### Developed by: Janagiraman.M 
### RegisterNumber: 212224230101
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
(i)
<img width="1196" height="524" alt="Screenshot 2025-08-28 092555" src="https://github.com/user-attachments/assets/67c1be75-c7f6-4a72-9378-48e4d502488f" />
<img width="1196" height="524" alt="Screenshot 2025-08-28 092601" src="https://github.com/user-attachments/assets/82f60bbd-c765-4cc8-85a9-e5409496e69a" />
(ii)
<img width="1203" height="771" alt="Screenshot 2025-08-28 092611" src="https://github.com/user-attachments/assets/11b34276-c9f0-4dc3-80f6-b33b6290619b" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

