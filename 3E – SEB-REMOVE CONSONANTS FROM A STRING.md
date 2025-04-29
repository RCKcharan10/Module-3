# Experiment No: 3e – SEB-Remove Consonants from a String

## AIM  
To write a Python function that accepts a string and removes all the consonants, retaining only vowels.

---

### ALGORITHM  
1. Begin the program.  
2. Define a function `remove(test)` that accepts a string as a parameter.  
3. Use list comprehension to iterate over each character in the string.  
4. Check if the character is a vowel (either lowercase or uppercase).  
5. Join the vowels into a new string.  
6. Print the resulting string.  
7. Terminate the program.

---

### 🧾 PROGRAM

```python
def remove(test):
    res = "".join([chr for chr in test if chr in 'aeiouAEIOU'])
    print(res)

remove("learning python")

```

### OUTPUT
![image](https://github.com/user-attachments/assets/ba0cfb6e-4ddf-4b3a-b898-a3bda18cde49)

### RESULT
Thus, the Python program to remove all consonants from a string and retain only vowels has been implemented and executed successfully.
