## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30}
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50}
def merge (dict1,dict2): 
   res={**dict1 , **dict2}
   return res 
dict3=merge(dict1,dict2)
print(dict3) 
```

## Output
<img width="561" height="136" alt="image" src="https://github.com/user-attachments/assets/eb66da1d-89ca-46aa-9389-23ad353092f8" />

## Result
Thus,the above program was executed succesfully.
