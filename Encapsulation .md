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
```
class Rectangle:
    __length = 0 
    __breadth = 0
    def __init__(self):
      self.__length = 5
      self.__breadth = 3
      print(self.__length)<img width="567" height="252" alt="image" src="https://github.com/user-attachments/assets/257bb0f9-1a12-45f9-b0e7-910468c559b0" />
      print(self.__breadth)
   
obj = Rectangle()
```
## Output
<img width="567" height="252" alt="image" src="https://github.com/user-attachments/assets/650852cc-2c0c-44f3-8d60-8a65b8a36fff" />


## Result
Thus the python program is executed successfully.
