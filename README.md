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
# Register No: 212225230291
# Developed By: VARSHA M
# 1-Norm of a Matrix
import numpy as np
A =  np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(norm1)



# 2-Norm of a Matrix
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,2)
print(f"{norm1:.2f}")




# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
result=np.linalg.norm(A,np.inf)
print(f"{result:.2f}")



```
## Output:
### 1-Norm of a Matrix
<img width="1197" height="592" alt="image" src="https://github.com/user-attachments/assets/49a63d55-2159-43a5-9776-1e21f37b2aff" />


### 2-Norm of a Matrix
<img width="1203" height="592" alt="image" src="https://github.com/user-attachments/assets/d65e7ce2-a4a6-4022-82d3-853b010da8a9" />



### Infinity Norm of a Matrix
<img width="1204" height="593" alt="image" src="https://github.com/user-attachments/assets/a8abc885-43b2-4001-af1c-9dd162e5849d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
