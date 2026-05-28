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
# Register No:212225247171
# Developed By:tharun
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# 2-Norm of a Matrix

# Type your code here
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)





```
## Output:
### 1-Norm of a Matrix
<img width="1393" height="820" alt="Screenshot 2026-05-29 020605" src="https://github.com/user-attachments/assets/cc4f4303-5366-452a-a292-018837ddef02" />

<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="1271" height="734" alt="Screenshot 2026-05-29 020740" src="https://github.com/user-attachments/assets/05dcb6c0-034a-4612-9bdd-74ef1fbc4cc5" />

<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="1357" height="858" alt="Screenshot 2026-05-29 020811" src="https://github.com/user-attachments/assets/f1ca072d-60d7-4876-8499-73fe99b59c8c" />

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
