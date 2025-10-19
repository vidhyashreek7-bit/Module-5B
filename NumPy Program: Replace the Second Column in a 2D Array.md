![5 1](https://github.com/user-attachments/assets/4433d104-ea3b-414b-b3a6-9d255c85acac)# NumPy Program: Replace the Second Column in a 2D Array

## 🎯 Aim
To write a **NumPy** program that deletes the second column from a given 2D array and inserts a new column at the same position.

## 🧠 Algorithm
1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Get a 2D NumPy array and a new column (as another array) from the user.
3. **Delete Column**: Use `np.delete()` to remove the second column (index 1) from the original array.
4. **Insert Column**: Use `np.insert()` to insert the new column at the second column's original position.
5. **Display Result**: Print the updated array with the replaced column.

## 🧾 Program
```
a=np.array(eval(input()))
b=np.array(eval(input()))
print("Printing Original array")
print(a)
print("Array after deleting column 2 on axis 1")
c=np.delete(a,1,axis=1) 
print(c)
print("Array after inserting column 2 on axis 1")
print(np.insert(c,1,b,axis=1))
```

## Output
![5 2](https://github.com/user-attachments/assets/80ab0c68-87e1-47d3-ad42-9ff02d69391c)


## Result
Thus the program is executed successfully.
