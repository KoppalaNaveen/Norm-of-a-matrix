# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No:
# Developed By:
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: KOPPALA NAVEEN
RegisterNumber: 212223100023
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/8a223dc9-94e8-425e-bbfc-cd080f8f119c)


### 2-Norm of a Matrix

![image](https://github.com/user-attachments/assets/b73288f3-3327-46da-8fbb-f3261386e3df)


### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/af9867a0-c5b3-4226-93d8-45b28a53d1ab)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
