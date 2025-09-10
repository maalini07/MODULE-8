# 🔍 Hackerrank:Python Program to Check if a String Ends with a Numeric Digit

This Python program checks whether the last character of a given input string is a **numeric digit (0–9)**.

---

## 🎯 Aim

To write a Python program that checks if a given string ends with a number using Python's built-in string methods.

---

## 🧠 Algorithm

1. **Start the program.**
2. **Input** a string from the user.
3. **Access** the last character using indexing (`string[-1]`).
4. **Check** if the last character is a digit using the `.isdigit()` method.
5. **If true**, print that the string ends with a number.
6. **Else**, print that the string does not end with a number.
7. **End the program.**

---

## 💻  Program
```
def ends_with_digit(s):
    return s[-1].isdigit() if s else False 
input_str = input("Enter a string: ")
if ends_with_digit(input_str):
    print("✅ The string ends with a numeric digit.")
else:
    print("❌ The string does NOT end with a numeric digit.")
```

## Output
<img width="518" height="132" alt="444352316-e0906845-6b20-4e8b-bcee-cfcd61ff2ee7" src="https://github.com/user-attachments/assets/6d4aaf9b-f54c-450d-b14e-e8e56e0693de" />

## Result
Thus, the program has executed successfully
