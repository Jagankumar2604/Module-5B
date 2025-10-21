# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np
a=np.array(eval(input()))
print("Given array ")
b=np.sort(a, axis=0)
print(f" {a}")
print("")
print(b)

```

## Output
<img width="751" height="645" alt="502987942-c018d95c-06c3-4122-9751-2227e4e67579" src="https://github.com/user-attachments/assets/4b9193e8-0f00-4e6c-bac7-23743f52a730" />



## Result
Thus,**NumPy** program that sorts the elements in each column of a given 2D array in ascending order is executed successfully.
