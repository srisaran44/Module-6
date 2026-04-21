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
# Encapsulation Example: Rectangle class
class Rectangle:
    def __init__(self, length, breadth):
        # Private member variables
        self.__length = length
        self.__breadth = breadth

    # Getter methods
    def get_length(self):
        return self.__length

    def get_breadth(self):
        return self.__breadth

    # Setter methods
    def set_length(self, length):
        if length > 0:
            self.__length = length
        else:
            print("Length must be positive!")

    def set_breadth(self, breadth):
        if breadth > 0:
            self.__breadth = breadth
        else:
            print("Breadth must be positive!")

    # Method to calculate area
    def calculate_area(self):
        return self.__length * self.__breadth


# Driver code
rect = Rectangle(10, 5)

print("Length:", rect.get_length())
print("Breadth:", rect.get_breadth())
print("Area:", rect.calculate_area())

# Updating values using setters
rect.set_length(15)
rect.set_breadth(8)

print("\nUpdated Length:", rect.get_length())
print("Updated Breadth:", rect.get_breadth())
print("Updated Area:", rect.calculate_area())

## Output
<img width="1068" height="608" alt="image" src="https://github.com/user-attachments/assets/5a3881ac-956f-4fef-ab26-50cab9c56ee0" />


## Result
