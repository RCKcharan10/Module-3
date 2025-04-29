# Experiment No: 3b Match Lowercase Sequence with '@' Using Regex

## AIM  
To write a Python program to find sequences of lowercase letters joined with a `'@'` using regular expressions.

---

### ALGORITHM  
1. Begin the program.  
2. Import the `re` module for regular expressions.  
3. Read a string input from the user.  
4. Use `re.search()` with the pattern `[a-z]+@` to search for a sequence of lowercase letters followed by `'@'`.
5. If a match is found, print **"Found a match!"**.
6. Otherwise, print **"Not matched!"**.
7. Terminate the program.

---

### 🧾 PROGRAM

```python
import re

a = input()
x = re.search("[a-z]+@", a)
if x:
    print("Found a match!")
else:
    print("Not matched!")

```
### OUTPUT
![image](https://github.com/user-attachments/assets/58347bbd-e236-4969-813f-a0bb62b9c8f4)

### RESULT
Thus, the Python program using regular expressions to find sequences of lowercase letters joined with '@' has been implemented and executed successfully.
