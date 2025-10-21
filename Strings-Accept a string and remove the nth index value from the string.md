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
def remove(a):
    n=int(input())
    x=""
    for i in range(len(a)):
        if i!=n:
            x+=a[i]
    return x
a=input()
print(remove(a))
```

## Output
<img width="1920" height="1080" alt="Screenshot 2025-10-20 215916" src="https://github.com/user-attachments/assets/ed0d6dd4-d210-4381-a3fd-10882c03ea9a" />


## Result
Thus the Python program that accepts a string and removes the character at a specified index executed successfully.
