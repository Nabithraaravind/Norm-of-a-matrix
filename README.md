# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
## Step 1 : Get the input matrix using np.array()
## Step 2 : Find the 1-norm of the matrix using np.linalg.norm(variable, 1)
## Step 3 : Find the 2-norm of the matrix using np.linalg.norm(variable, 2)
## Step 4 : Find the infinity-norm of the matrix using np.linalg.norm(variable, np.inf)
## Step 5 : Print the norm of the matrix in two decimal places and end the program.

## Program:
```Python
# Register No:24005092
# Developed By:A.Nabithra
```
## 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-03 204822](https://github.com/user-attachments/assets/d7a3a848-5ca9-4437-aa17-dbd1fad27fb8)

### 2-Norm of a Matrix
![Screenshot 2024-12-03 204837](https://github.com/user-attachments/assets/aa8cce32-8663-4d25-842b-3e4824e8eb8e)

### Infinity Norm of a Matrix
![Screenshot 2024-12-03 204909](https://github.com/user-attachments/assets/62396238-99fb-4578-a842-b0cfddaf6438)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
