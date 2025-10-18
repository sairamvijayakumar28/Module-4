# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
import csv
with open('story.csv', 'w') as f:
    f.write("The sun rise in east\n")
    f.write("Hello guy.\n")

count = 0
with open('story.csv', 'r') as file:
    for line in file:
        if not line.startswith('T'):
            count += 1

print("Lines not starting with 'T':", count)
```

## Output

<img width="1121" height="287" alt="image" src="https://github.com/user-attachments/assets/3dc3348e-5058-44f6-81d8-dfaa99ec5de7" />

## Result
Thus,the above program was executed succesfully.
