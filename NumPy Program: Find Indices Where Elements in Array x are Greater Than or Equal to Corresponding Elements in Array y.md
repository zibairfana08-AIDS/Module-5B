# # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

## 🎯 Aim
To write a Python program using **NumPy** that finds the indices where elements in array `x` are greater than or equal to their corresponding elements in array `y`.

## 🧠 Algorithm
1. **Import NumPy**: Import the NumPy library.
2. **Define Arrays**: Define two NumPy arrays, `x` and `y`, with the same shape (i.e., same number of elements).
3. **Use Boolean Indexing**: 
   - `x > y` gives a boolean array where elements of `x` are greater than `y`.
   - `x == y` gives a boolean array where elements of `x` are equal to `y`.
4. **Find Indices**: Use `np.where()` to get the indices where the conditions `x >= y` are satisfied.
5. **Print Indices**: Print the indices where the condition holds true.

## 🧾 Program
```
import numpy as np


x = np.array([10, 25, 30, 5, 18])
y = np.array([8, 25, 20, 10, 15])


condition = x >= y 

indices = np.where(condition)[0]


print("Array x:", x)
print("Array y:", y)
print("Indices where x >= y:", indices)
```

## Output
<img width="892" height="395" alt="502948978-5795c24e-f3a4-4909-896f-2df36e5f7b39" src="https://github.com/user-attachments/assets/34c38a56-7f02-4412-b0b8-ef4ae3c809de" />

## Result
a Python program using NumPy that finds the indices where elements in array x are greater than or equal to their corresponding elements in array y is executed successfully.
