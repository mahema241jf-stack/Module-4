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
list1 = [10, 20, 30]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```

## Output
<img width="415" height="144" alt="{9DE9ACC7-CC56-46DE-96E7-9365200D9447}" src="https://github.com/user-attachments/assets/f259b7f4-1e0e-4158-9808-a49c922be718" />


## Result
The program successfully handles an IndexError using a try-except block. When an out-of-range index is accessed, it catches the error and displays the message "You're out of list range".
