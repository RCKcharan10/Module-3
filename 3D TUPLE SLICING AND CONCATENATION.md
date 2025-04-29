# Experiment No: 3d -Tuple Slicing and Concatenation

## AIM  
To write a Python function that gets two tuples, slices the first tuple between indices 2 and 5, and concatenates the sliced tuple with the second tuple.

---

### ALGORITHM  
1. Begin the program.  
2. Define a function `tuples()` with no arguments.  
3. Read two tuples from the user using `eval(input())`.  
4. Print both tuples.  
5. Slice the first tuple from index 2 to 5 (excluding 5).  
6. Concatenate the sliced tuple with the second tuple.  
7. Print the resultant tuple.  
8. Terminate the program.

---

### 🧾 PROGRAM

```python
def tuples():
    tuples1 = eval(input())
    tuples2 = eval(input())
    
    print(f"tuple1={tuples1}")
    print(f"tuple2={tuples2}")
    
    sliced_tuple = tuples1[2:5]
    result = sliced_tuple + tuples2
    
    print(f"Resultant tuple={result}")

tuples()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/87e8f367-910b-47ec-9f05-761e6db00240)

### RESULT
Thus, the Python program for tuple slicing and concatenation has been implemented and executed successfully.
