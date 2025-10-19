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

mat = np.array(eval(input()))

ans = np.linalg.norm(mat,2)

norm_matrix = "{:.2f}".format(ans)

print(norm_matrix)


# Infinity Norm of a Matrix


import numpy as np

mat = np.array(eval(input()))

ans = np.linalg.norm(mat,np.inf)

norm_matrix = "{:.2f}".format(ans)

print(norm_matrix)



## Output:
### 1-Norm of a Matrix

<img width="564" height="203" alt="image" src="https://github.com/user-attachments/assets/74f0ffab-69c4-4437-b615-4db5b04299c8" />


### 2-Norm of a Matrix

<img width="572" height="236" alt="image" src="https://github.com/user-attachments/assets/c21097b7-5212-4bd1-842a-d015671595a0" />


### Infinity Norm of a Matrix

<img width="597" height="199" alt="image" src="https://github.com/user-attachments/assets/a3224913-b7ad-4248-8565-6f537b995c71" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
