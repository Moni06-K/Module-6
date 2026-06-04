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
```
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


# Generic function
def func(obj):
    obj.type()
    obj.color()


# Create objects
b = Beans()
m = Mango()

# Call function with different objects
func(b)
func(m)
```


## Output
<img width="972" height="617" alt="image" src="https://github.com/user-attachments/assets/837813a0-2c90-49b5-9b01-e22a47911613" />
<img width="1170" height="240" alt="image" src="https://github.com/user-attachments/assets/f6c010e0-f81a-4a49-a753-67b5265b513f" />

## Result
execution of program is completed
