# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30, 40]

try:
    print("Enter the index :", list1[5])
except IndexError:
    print("You're out of list range")
```

## Output

<img width="469" height="168" alt="image" src="https://github.com/user-attachments/assets/efef75a0-8e3f-4ef7-90d4-5ae9187542db" />

## Result
Thus,the above program was executed succesfully.
