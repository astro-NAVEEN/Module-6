# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
# Polymorphism with Classes in Python

class Beans:

    def type(self):
        print("Vegetable")

    def color(self):
        print("Green")


class Mango:

    def type(self):
        print("Fruit")

    def color(self):
        print("Yellow")


# Generic function demonstrating polymorphism
def func(obj):

    obj.type()
    obj.color()


# Object creation
b = Beans()

m = Mango()

# Function calls
func(b)

func(m)

## Output
<img width="604" height="455" alt="Screenshot 2026-05-31 145903" src="https://github.com/user-attachments/assets/7ec49236-baf6-42af-9cf8-54dd463e8b68" />


## Result
Thus, the Python program demonstrating polymorphism using classes and a generic function was successfully written and executed.
