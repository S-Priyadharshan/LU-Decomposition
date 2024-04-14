# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1) Import the necessary library for LU decomposition.

2) Decompose the input matrix into lower triangular matrix (L) and upper triangular matrix (U).

3) Return the L and U matrices.

4) Call the LU decomposition function with the input matrix as argument.

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Priyadharshan S 
RegisterNumber: 212223240127
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Priyadharshan S
RegisterNumber: 212223240127
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
b=np.array(eval(input()))
soln=np.linalg.solve(matrix,b)
print(soln)
```

## Output:

![image](https://github.com/S-Priyadharshan/LU-Decomposition/assets/145854138/87997486-74ef-4578-95b0-c0672d474638)

![image](https://github.com/S-Priyadharshan/LU-Decomposition/assets/145854138/810ee651-c38b-44db-ad8c-5af3e6b9645e)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

