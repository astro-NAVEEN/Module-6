# 🐍 Python OOP: Abstract Class & Method Example

## 🎯 AIM

To create an **abstract class** named `Shape` with an **abstract method** `calculate_area`, and implement this method in two subclasses: `Rectangle` and `Circle`.

---

## 🧠 ALGORITHM

1. **Import ABC module**:
   - Use `from abc import ABC, abstractmethod` to define abstract classes and methods.

2. **Create Abstract Class `Shape`**:
   - Define an abstract method `calculate_area()` with `@abstractmethod`.

3. **Create Subclass `Rectangle`**:
   - Set default values for `length` and `breadth`.
   - Override `calculate_area()` to compute the rectangle area.

4. **Create Subclass `Circle`**:
   - Set default value for `radius`.
   - Override `calculate_area()` to compute the circle area.

5. **Create Objects & Call Methods**:
   - Instantiate `Rectangle` and `Circle`.
   - Call their `calculate_area()` methods.

---

## 💻 Program
 from abc import ABC, abstractmethod

# Abstract Class
class Shape(ABC):

    @abstractmethod
    def calculate_area(self):
        pass


# Subclass Rectangle
class Rectangle(Shape):
    def __init__(self, length, breadth):
        self.length = length
        self.breadth = breadth

    def calculate_area(self):
        area = self.length * self.breadth
        print("Area of Rectangle:", area)


# Subclass Circle
class Circle(Shape):

    def __init__(self, radius):
        self.radius = radius

    def calculate_area(self):
        pi = 3.14
        area = pi * self.radius * self.radius
        print("Area of Circle:", area)


# Object creation
r = Rectangle(10, 5)

c = Circle(7)

# Method calls
r.calculate_area()

c.calculate_area()

## Output
<img width="659" height="366" alt="Screenshot 2026-05-31 145119" src="https://github.com/user-attachments/assets/1b87bcf0-2135-4d47-9db7-477413ff7fcc" />


## Result
Thus, the Python program demonstrating abstraction using an abstract class and method was successfully written and executed using Shape, Rectangle, and Circle classes.
