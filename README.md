# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. get the array as input
3. assign the values to that
4. print the result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: K.KAAVIYAN
RegisterNumber: 212224240066
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: K.KAAVIYAN
RegisterNumber: 212224240066
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
```

## Output:
# 1 st:
![Screenshot 2025-04-26 143012](https://github.com/user-attachments/assets/a8bdf012-9094-406a-944b-0d25978df725)
# 2 nd:
![Screenshot 2025-04-26 143022](https://github.com/user-attachments/assets/5650ab9e-8ce3-4ffd-9bcd-4d688c120e9c)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
