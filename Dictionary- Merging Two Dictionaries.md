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
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}

def merge():
    merged_dict = {**dict1, **dict2}
    print(merged_dict)

merge()
```

## Output
<img width="457" height="224" alt="{40A1B7F5-FBC6-4901-BDB8-ECBE354B50D8}" src="https://github.com/user-attachments/assets/90381090-4511-427a-b665-9be4f579300c" />

## Result
The program successfully merges two dictionaries using the ** unpacking operator and prints the merged dictionary. If a key exists in both dictionaries, the value from dict2 overwrites the value from dict1.
