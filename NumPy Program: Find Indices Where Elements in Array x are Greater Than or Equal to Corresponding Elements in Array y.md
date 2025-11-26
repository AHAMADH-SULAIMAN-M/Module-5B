<img width="820" height="490" alt="image" src="https://github.com/user-attachments/assets/6bc013e8-272e-4103-ae00-082604776834" /># # NumPy Program: Find Indices Where Elements in Array x are Greater Than or Equal to Corresponding Elements in Array y

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

```python
import numpy as np   # Import NumPy

x = np.array([5, 8, 3, 10, 7])
y = np.array([2, 8, 4, 6, 7])

greater_than = x > y
equal_to = x == y

indices = np.where(x >= y)

# Print results
print("x:", x)
print("y:", y)

print("\nBoolean array (x > y):", greater_than)
print("Boolean array (x == y):", equal_to)

print("\nIndices where x >= y:", indices)

```

## Output

<img width="820" height="490" alt="image" src="https://github.com/user-attachments/assets/b6239b2f-5331-4a78-adea-6314596d1f60" />

## Result
The python program using numpy that finds the indices where elements  in array x are greater than or equal to thier corressponding elements in array y is executed Successfully and verified.
