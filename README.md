# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	
Step 1:
Get the input matrix using np.array()

Step 2:
Find the 1-norm,2-norm,infinity norm of the matrix using np.linalg.norm()

Step 3:
Print the norm of the matrix in two decimal places.

Step 4:
End the program.

Program:
## Program:
```Python
# Register No: 212224240175
# Developed By: THEJASHREE S
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix


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
<img width="1171" height="347" alt="image" src="https://github.com/user-attachments/assets/add0d395-aa5c-465a-b6d8-249b9da2f18d" />


### 2-Norm of a Matrix
<br>
<br>
<br><img width="1176" height="385" alt="image" src="https://github.com/user-attachments/assets/ce14a866-2269-48d0-880b-2013967ee84e" />


### Infinity Norm of a Matrix
<br>
<br>
<br><img width="1263" height="353" alt="image" src="https://github.com/user-attachments/assets/628160d1-ccef-4b9d-aa75-4fd26f7e7396" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
