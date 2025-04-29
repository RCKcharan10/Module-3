# Experiment No: 2h – SEB-List Index-Based Multiplication

## AIM  
To write a Python function that takes a list `L` as an argument, multiplies 10 to the value at the even index and 5 to the value at the odd index, and displays the modified list `L`.

---

### ALGORITHM  
1. Begin the program.  
2. Define a function `add(L)` that accepts a list `L` as an argument.  
3. Use a `for` loop to iterate over the indices of the list.  
4. For each index `i`:
   - If `i` is even (`i % 2 == 0`), multiply `L[i]` by 10.
   - Else, multiply `L[i]` by 5.
5. Print the updated list `L`.
6. Read the list from the user or provide it directly.
7. Call the `add()` function with the list as an argument.
8. Terminate the program.

---

### 🧾 PROGRAM

```python
def add(L):
    for i in range(0, len(L)):
        if i % 2 == 0:
            L[i] = L[i] * 10
        else:
            L[i] = L[i] * 5
    print(L)

add([20, 30, 8, 110, 70, 92, 12])

```

### OUTPUT
![image](https://github.com/user-attachments/assets/41799199-8ab0-4ec9-b7df-0a3d90ebaf94)

### RESULT
Thus, the Python function that modifies a list by multiplying 10 to even indices and 5 to odd indices has been implemented and executed successfully.
