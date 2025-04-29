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
list1=[5, 10, 20]
try:
    print(list1[5])
except IndexError:
    msg="You're out of list range"
    print(msg)
```

## Output
![Screenshot 2025-04-29 201452](https://github.com/user-attachments/assets/995b549c-5da4-4ba8-96fd-ca1546b92512)


## Result
     A python program that handles an **IndexError** when trying to access an element beyond the available range of a list,is successfully executed.

