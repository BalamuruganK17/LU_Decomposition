# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. First import numpy as np
2. Next from scipy.linalg import the required element
3. Declare required variable or variables as the input for the array of elements
4. Finally print L and U or x to find values of L and U or LU Decomposition

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P ,L ,U = lu(A)
print(L)
print(U)
```
Developed by: BALAMURUGAN.K
RegisterNumber: 25017932

Screenshot: <img width="1471" height="760" alt="Screenshot 2025-11-24 100023" src="https://github.com/user-attachments/assets/d99af81f-cf7d-41d5-963d-9ed10c0c44d1" />

```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```
Developed by: BALAMURUGAN.K
RegisterNumber: 25017932

Screenshot: <img width="1447" height="739" alt="Screenshot 2025-11-24 100209" src="https://github.com/user-attachments/assets/ae9e843f-ada4-4284-bd2a-8d5d70b97780" />

```

## Output1:<img width="1442" height="610" alt="Screenshot 2025-11-24 100100" src="https://github.com/user-attachments/assets/4a3335f4-7ce4-45f6-a994-dc0610c8b8dd" />

## Output2:<img width="1474" height="341" alt="Screenshot 2025-11-24 100223" src="https://github.com/user-attachments/assets/3920bd66-2525-46d4-a852-a7e24953f911" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

