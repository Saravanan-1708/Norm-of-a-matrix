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
# Register No: saravanan R
# Developed By: 26008206
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
norm="{:.2f}".format(norm1)
print(norm)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,2)
norm="{:.2f}".format(norm1)
print(norm)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,np.inf)
norm="{:.2f}".format(norm1)
print(norm)




```
## Output:
### 1-Norm of a Matrix
<br><img width="1322" height="852" alt="image" src="https://github.com/user-attachments/assets/76cfb79f-466b-4a86-af01-edca8a162c22" />

<br>
<br>

### 2-Norm of a Matrix
<br><img width="1372" height="862" alt="image" src="https://github.com/user-attachments/assets/b521b6e2-62f1-405b-8f4b-f46a2722b382" />

<br>
<br>

### Infinity Norm of a Matrix
<br><img width="1295" height="822" alt="image" src="https://github.com/user-attachments/assets/2d24dbe3-afac-41b3-acd2-ae131ce28263" />

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
