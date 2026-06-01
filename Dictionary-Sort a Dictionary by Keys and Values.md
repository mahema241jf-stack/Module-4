# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
dictionary = {
    'c': 3,
    'a': 1,
    'b': 2,
    'd': 4
}

print("Original Dictionary:", dictionary)

sorted_by_keys = dict(sorted(dictionary.items()))
print("Sorted by Keys:", sorted_by_keys)

sorted_by_values = dict(sorted(dictionary.items(), key=lambda item: item[1]))
print("Sorted by Values:", sorted_by_values)
```

## Sample Output
<img width="702" height="246" alt="{700052C8-C677-49DB-8D89-5D290A934587}" src="https://github.com/user-attachments/assets/f7234963-196e-4bd5-ae2e-c3d24d2dd987" />


## Result
The program successfully sorts the dictionary by keys and by values using the sorted() function and displays the original dictionary along with the sorted dictionaries.
