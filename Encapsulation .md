# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
# Encapsulation with Private Members in Python

class Rectangle:

    def __init__(self, length, breadth):
        self.__length = length      # private variable
        self.__breadth = breadth    # private variable

    def display(self):
        print("Length:", self.__length)
        print("Breadth:", self.__breadth)


# Object creation
r = Rectangle(10, 5)

# Display values
r.display()

## Output
<img width="616" height="407" alt="Screenshot 2026-05-31 145333" src="https://github.com/user-attachments/assets/f3ae858c-4a7d-4215-8e7f-70d54e5113b2" />


## Result
Thus, the Python program demonstrating encapsulation using private members in a class was successfully written and executed using the Rectangle class.
