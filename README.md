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
# Register No: 212224230297
# Developed By: s vasunthara sai
# 1-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,1)
Norm="{:.2f}".format(a)
print(Norm)



# 2-Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,2)
Norm="{:.2f}".format(a)
print(Norm)



# Infinity Norm of a Matrix
import numpy as np
m=np.array(eval(input()))
a=np.linalg.norm(m,np.inf)
Norm="{:.2f}".format(a)
print(Norm)



```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>

### 2-Norm of a Matrix
<br>
<br>
<br>

### Infinity Norm of a Matrix
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
