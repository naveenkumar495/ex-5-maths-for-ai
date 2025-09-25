# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
1:Define the package as scipy.linalg import lu.
2:Get input from user and print L and U matrix by 'print' .
3:Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4:print the variable 'X'
```
## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by:Naveenkumar M 
RegisterNumber: 212224230183
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
p,L,U = lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by:Naveenkumar M
RegisterNumber:212224230183
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu, pivot =lu_factor(A)
result = lu_solve((lu,pivot),B)
print(result)
```


## Output:
<img width="1120" height="1024" alt="image" src="https://github.com/user-attachments/assets/2e3ae6f5-7eea-428a-b0df-9fa3e37b64f5" />
<img width="1156" height="838" alt="image" src="https://github.com/user-attachments/assets/3d348059-35e4-4971-8d9d-72c9d43759ba" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

