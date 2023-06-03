# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the NumPy library using the statement import numpy as np. 
2. Import the lu function from the scipy.linalg module using the statement from scipy.linalg import lu. 
3. Get the inputs.
4. Print the solution

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: AdhithyaRam D
RegisterNumber: 212222230008
*/
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
Developed by: AdhithyaRam D
RegisterNumber: 212222230008
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
b=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot 2023-06-03 141246](https://github.com/Adhithyaram29D/LU-Decomposition/assets/119393540/ecf71b4a-e4d5-4796-8e19-ad84d691125a)

![Screenshot 2023-06-03 141802](https://github.com/Adhithyaram29D/LU-Decomposition/assets/119393540/8b8c6983-c50d-441b-b45c-db1fb27c2868)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

