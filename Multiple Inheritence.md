# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
```
class Calculation1:
    def Summation(self, a, b):
        return a + b


class Calculation2:
    def Subtraction(self, a, b):
        return a - b


class Derived(Calculation1, Calculation2):
    def Division(self, a, b):
        return a / b


a = float(input("Enter first number: "))
b = float(input("Enter second number: "))

obj = Derived()

sum_result = obj.Summation(a, b)
sub_result = obj.Subtraction(a, b)
div_result = obj.Division(a, b)

print("Summation:", sum_result)
print("Subtraction:", sub_result)
print("Division:", div_result)
```
## Output Example

<img width="282" height="173" alt="image" src="https://github.com/user-attachments/assets/790c9bb8-0f45-4103-bebd-559d40516472" />

## RESULT
Thus the program executed successfully.


