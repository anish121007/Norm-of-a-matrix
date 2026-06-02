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
# Register No: 212225240010
# Developed By: anish k b
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm = "{:.2f}".format(ans)
print(norm)




# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"
import numpy as np
m = np.array(eval(input()))
a = np.linalg.norm(m,2)
n="{:.2f}".format(a)
print(n)





# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np
m=np.array(eval(input()))
ans=np.linalg.norm(m,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)






```
## Output:
### 1-Norm of a Matrix
<img width="1176" height="202" alt="Screenshot 2026-06-02 065348" src="https://github.com/user-attachments/assets/0391e017-a082-47c7-bc34-18a37019665f" />


### 2-Norm of a Matrix
<img width="1180" height="263" alt="Screenshot 2026-06-02 065400" src="https://github.com/user-attachments/assets/f7674f58-0b96-458f-9da1-b68d33f5b56f" />

### Infinity Norm of a Matrix
<img width="1193" height="218" alt="Screenshot 2026-06-02 065413" src="https://github.com/user-attachments/assets/1aced5b3-8080-416b-9b17-6d3be43e24bd" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified. 
