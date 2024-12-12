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
# Register No:24004502
# Developed By: Rithik Ram.S

# 1-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,1)
Norm_of_matrix=f"{ans:.2f}"
print(Norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,2)
L2_Norm_of_matrix=f"{ans:.2f}"
print(L2_Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
Norm_of_matrix=f"{ans:.2f}"
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-12 211249](https://github.com/user-attachments/assets/cab79306-e3fa-4e3e-b5f3-80245d82f7d1)


### 2-Norm of a Matrix
![Screenshot 2024-12-12 211318](https://github.com/user-attachments/assets/cfb21f4c-f4c5-4240-a3b5-411fedd27856)

### Infinity Norm of a Matrix
![Screenshot 2024-12-12 211340](https://github.com/user-attachments/assets/c474a3ac-7d3c-4393-8864-c170167455f2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
