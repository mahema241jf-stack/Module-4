# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program

```
class cse:
    def mech(self, r):
        area = 3.14 * r * r
        print("Area of the circle =", area)

r = float(input("Enter the radius: "))

obj = cse()
obj.mech(r)
```

## Output
<img width="398" height="166" alt="{39131BC9-93A0-4EE9-9C57-2DAAD3FA96E3}" src="https://github.com/user-attachments/assets/96bceab8-6429-40ac-813e-d41ae6fea8d1" />

## Result
The program successfully creates a class cse with a method mech to calculate the area of a circle using the formula Area = πr² and displays the calculated area for the given radius.

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

