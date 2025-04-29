# Experiment No: 3a -String Character Conversion

## AIM  
To write a Python program using a function `convert` that accepts a string and:
- Converts uppercase characters to lowercase,
- Converts lowercase characters to uppercase, and
- Replaces numbers with `*` using `if..elif` statements.

---

### ALGORITHM  
1. Begin the program.
2. Define a function `convert(str)` that accepts a string as input.
3. Initialize an empty string `r` to store the result.
4. Iterate through each character in the input string:
   - If the character is a lowercase letter, convert it to uppercase and append to `r`.
   - Else if the character is an uppercase letter, convert it to lowercase and append to `r`.
   - Else (for digits and other characters), append `'*'` to `r`.
5. Print the final converted string.
6. Use `input()` to read the string from the user and call the `convert` function with it.
7. Terminate the program.

---

### 🧾 PROGRAM

```python
def convert(str):
    r = ""
    for i in str:
        if i.islower():
            r += i.upper()
        elif i.isupper():
            r += i.lower()
        elif i.isdigit():
            r += '*'
        else:
            r += i
    print(r)

s = input()
convert(s)

```

### OUTPUT
![image](https://github.com/user-attachments/assets/0d1c9bbd-dd5b-4637-98f4-970366722a0c)

### RESULT
Thus, the Python program that defines a function to convert character cases and replace digits using if..elif statements has been implemented and executed successfully.
