# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step1:
 Get the input matrix using np.array()   
## Step2:
 Find the 2-norm of the matrix using np.linalg.norm()
 ## Step3:
  Print the norm of the matrix in two decimal places.

## Program:
```
# Developed by: P.Sasinthar
# RegisterNumber: 23012532
# 1-Norm of the Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of the  Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
import numpy as np 
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```

## Output:
### 1-Norm of a Matrix
![Alt text](<Screenshot 2023-12-24 201033.png>)

### 2-Norm of a Matrix
![Alt text](<Screenshot 2023-12-24 201056.png>)

### Infinity Norm of a Matrix
![Alt text](<Screenshot 2023-12-24 201149.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
