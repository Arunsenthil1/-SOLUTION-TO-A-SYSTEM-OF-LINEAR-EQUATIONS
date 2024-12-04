# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:04/12/2024
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
```
import numpy as np

# Coefficient matrix A
A = np.array([[5, -3, -10],
              [2, 2, -3],
              [-3, -1, 5]])

# Constant matrix B
B = np.array([-9, 4, -1])

# Solve for X using numpy's linear algebra solver
X = np.linalg.solve(A, B)

# Convert the solution to integers where appropriate
x, y, z = X

# Output the solution without unnecessary decimals
print(f"{X}")
```


## Output:
![Screenshot 2024-12-04 183126](https://github.com/user-attachments/assets/dea6e228-966b-473c-aa43-5bb32d7eeb9e)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

