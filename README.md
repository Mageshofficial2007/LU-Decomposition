# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation. 
2.Prepare the lists from each linear equations and assign in np.array().
3.Using the scipy.linalg.solve(),and import lu decomposition,we can find the solutions.
4.End the program

## Program:
(i) To find the L and U matrix
```python
Program to find the L and U matrix.
Developed by:MAGESH BOOPATHI.M
RegisterNumber:212224230145
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
Program to find the LU Decomposition of a matrix.
Developed by:MAGESH BOOPATHI.M
RegisterNumber:212224230145 
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
piv,lu=lu_factor(a)
result=lu_solve((piv,lu),b)
print(result)
```

## Output:
![lu decomposition](<Screenshot 2025-04-11 113721.png>)
![lu decomposition](<Screenshot 2025-04-11 113744.png>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

