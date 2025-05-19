# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import required libraries numpy and scipy.linalg.

2. Input the matrix/matrices using eval(input()).

3. Perform LU decomposition using lu() or solve equations using lu_factor() and lu_solve().

4. Print the results L and U matrices or solution X matrix.
## Program:
(i) To find the L and U matrix

```
Program to solve a matrix using LU decomposition.
Developed by: Suruthi S
RegisterNumber: 212224220114
```
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
Program to find the LU Decomposition of a matrix.
Developed by:SURUTHI S 
RegisterNumber:212224220114
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
![Screenshot 2025-04-29 205134](https://github.com/user-attachments/assets/9aa0e4b9-59a3-49d3-946e-35a3c9a16f9b)
![Screenshot 2025-04-29 205146](https://github.com/user-attachments/assets/3100a8e7-b963-4ee6-90af-892e53405b8b)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

