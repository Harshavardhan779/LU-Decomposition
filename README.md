# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Harsahvardhan
RegisterNumber: 22007173
*/
```
```python 
'''Program to find L and U matrix using LU decomposition.
Developed by: Harshavardhan
RegisterNumber: 22007173
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
/*
Program to find the LU Decomposition of a matrix.
Developed by: Harshavardhan
RegisterNumber: 22007173
*/
```
```python
'''Program to solve a matrix using LU decomposition.
Developed by: Harshavardhan
RegisterNumber: 22007173
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![lu decomposition](/WhatsApp%20Image%202023-01-11%20at%2021.42.44%20(1).jpeg)
![lu decomposition](/WhatsApp%20Image%202023-01-11%20at%2021.42.44.jpeg)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

