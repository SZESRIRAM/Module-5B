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
a=np.array(eval(input()))
b=np.array(eval(input()))
print(np.where(a>b))
print(np.where(a==b))
```
## Output
<img width="431" height="200" alt="image" src="https://github.com/user-attachments/assets/e93f59d0-3de7-48b6-8de2-9b3e96aca335" />
<img width="366" height="164" alt="image" src="https://github.com/user-attachments/assets/51c48664-bb07-4876-8622-cf28d2bcc6ab" />

## Result
Thus, the given program has been executed successfully and the indices where elements of array a are greater than or equal to elements of array b are identified using NumPy.
