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
# Parent class
class Fish:
    def type(self):
        print("I am a generic fish.")

# Child class (inherits from Fish)
class Shark(Fish):
    # Overriding the type method
    def type(self):
        print("I am a Shark, a specific type of fish.")

# Driver code
f = Fish()
s = Shark()

f.type()   # Calls parent class method
s.type()   # Calls child class overridden method



## OUTPUT
<img width="1087" height="763" alt="image" src="https://github.com/user-attachments/assets/046b3b61-28ea-41c4-a0cc-486e498ea8b3" />



## RESULT
