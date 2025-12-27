# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program
```

class Demo:
    def __init__(self):
        self.status = "Alive"
        print(self.status)
    def __del__(self):
        print("Object is being destroyed")
obj = Demo()
del obj
```
## 🧪 Output

<img width="236" height="39" alt="image" src="https://github.com/user-attachments/assets/5425be1f-a35e-4a98-a98c-733a2a430885" />

## Result
Thus the program executed successfully.
