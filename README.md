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
# Register No: 212225220024
# Developed By: dharshini
```
```
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
```
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
```
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```
## Output:
### 1-Norm of a Matrix
<img width="859" height="367" alt="Screenshot 2026-06-04 100051" src="https://github.com/user-attachments/assets/75ad00fb-9443-46b5-b899-313082d81aad" />

### 2-Norm of a Matrix
<img width="863" height="402" alt="Screenshot 2026-06-04 100117" src="https://github.com/user-attachments/assets/47051638-e815-46d6-8798-3255bfe12b58" />

### Infinity Norm of a Matrix
<img width="768" height="399" alt="Screenshot 2026-06-04 100134" src="https://github.com/user-attachments/assets/29c7f7a9-d0a9-47d7-b1e2-0f55a579150d" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
