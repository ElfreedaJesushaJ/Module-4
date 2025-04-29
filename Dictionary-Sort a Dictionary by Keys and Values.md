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
from collections import OrderedDict
def dictionary():
    dictionary={}
    from collections import OrderedDict
def dictionary():
    dictionary={}
    dictionary[2]=56
    dictionary[1]=2
    dictionary[5]=12
    dictionary[4]=24
    dictionary[6]=18
    dictionary[3]=323
    print("Keys and Values sorted in alphabetical order by the value")
    print(sorted(dictionary.items(),key=lambda kv:kv[1]))
dictionary()

```

## Sample Output
![Screenshot 2025-04-29 201040](https://github.com/user-attachments/assets/6a054e83-6568-4898-bf3f-003c7b5ed954)


## Result
      A python program that sorts a dictionary's keys in alphabetical order and values in alphabetical order,is successfully executed.


