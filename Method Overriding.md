# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
# Method Overriding - Fish and Shark Class Inheritance

class Fish:

    def type(self):
        print("fish")


class Shark(Fish):

    def type(self):
        print("shark")


# Objects creation
obj_goldfish = Fish()

obj_hammerhead = Shark()

# Loop through objects
for obj in (obj_goldfish, obj_hammerhead):

    obj.type()

## OUTPUT
<img width="569" height="449" alt="Screenshot 2026-05-31 145546" src="https://github.com/user-attachments/assets/823abe04-4dc8-48c4-99ad-91e17ab2807e" />


## RESULT
Thus, the Python program demonstrating method overriding using inheritance with Fish and Shark classes was successfully written and executed.
