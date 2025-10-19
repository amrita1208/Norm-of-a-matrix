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


# Register No:25011865
# Developed By:M.AMRITA
# 1-Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_matrix = "{:.2f}".format(ans)
print(norm_matrix) 


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_matrix = "{:.2f}".format(ans)
print(norm_matrix)


# Infinity Norm of a Matrix

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)

## Output:
### 1-Norm of a Matrix

<img width="575" height="210" alt="image" src="https://github.com/user-attachments/assets/bf2da89d-9f98-46cb-b1f3-660ab93ffd1b" />


### 2-Norm of a Matrix

<img width="548" height="251" alt="image" src="https://github.com/user-attachments/assets/7f5c00de-9002-4bc4-867f-ec2952d28301" />


### Infinity Norm of a Matrix

<img width="586" height="201" alt="image" src="https://github.com/user-attachments/assets/21a7bcd8-7b21-4a08-8dc1-f14c5fbeaf6c" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
