# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:
import numpy as np

### Step 2:
from scipy package import lu

### Step 3:
get input from the user

### Step 4:
print result
## Program:
(i) To find the L and U matrix

```
Program to find the L and U matrix.
Developed by:SURUTHI S
RegisterNumber:212224220114

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix

```
Program to find the LU Decomposition of a matrix.
Developed by:SURUTHI S 
RegisterNumber:212224220114

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),B)
print(x)
```

## Output:
![Screenshot 2025-04-29 205134](https://github.com/user-attachments/assets/9aa0e4b9-59a3-49d3-946e-35a3c9a16f9b)
![Screenshot 2025-04-29 205146](https://github.com/user-attachments/assets/3100a8e7-b963-4ee6-90af-892e53405b8b)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

