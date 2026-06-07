# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```
def remove(string, n):
    a = ""
    for i in range(len(string)):
        if i != n:
            a += string[i]
    return a

input_string = input("Enter a string: ")
index_to_remove = int(input("Enter the index to remove: "))

result = remove(input_string, index_to_remove)
print("Modified string:", result)
```

## Output
<img width="336" height="259" alt="image" src="https://github.com/user-attachments/assets/f2f108ff-5b00-4837-b9ca-b267c1e03916" />

## Result
The Python program that accepts a string and removes the character at a specified index has been written and the output is verified.

