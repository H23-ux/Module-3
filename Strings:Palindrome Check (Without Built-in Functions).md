# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program

```
s = "google"
reversed_s = s[::-1]

if s == reversed_s:
    print(f"'{s}' is a palindrome")
else:
    print(f"'{s}' is not a palindrome")
```

## Output

<img width="411" height="273" alt="image" src="https://github.com/user-attachments/assets/8e3ccf06-4bc5-4706-89c0-f2c145158c66" />

## Result
The Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions has been written and verified.
