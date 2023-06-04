# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy library using import statement
2. From scipy package import lu()
3. Get input from user and pass it as an array.
4. Get P, L, U matrix using lu()
5. Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Jeyabalan
RegisterNumber: 212222240040
*/
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
/*
Program to find the LU Decomposition of a matrix.
Developed by: Jeyabalan
RegisterNumber: 212222240040
*/
```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

```

## Output:
![lu decomposition]()![image](https://github.com/jeyaqbalan7/LU-Decomposition/assets/119393851/9b51b595-8890-49de-90ff-a80b33af4e1f)
![image](https://github.com/jeyaqbalan7/LU-Decomposition/assets/119393851/3e5adf39-b56a-47e2-a293-29979e0c6731)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

