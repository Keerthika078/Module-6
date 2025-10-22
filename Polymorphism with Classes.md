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
class Beans(): 
       def type(self): 
         print("Vegetable") 
       def color(self):
         print("Green") 
  class Mango(): 
       def type(self): 
         print("Fruit") 
       def color(self): 
         print("Yellow")      
  def func(obj): 
      obj.type()
      obj.color()
  obj_Beans=Beans()
  obj_mango=Mango()
  func(obj_Beans) 
  func(obj_mango)
```
## Output
![bf4f3a89-7fa6-454a-8f72-c406d31d7e01](https://github.com/user-attachments/assets/a4e49d72-3b55-4129-a10c-a3a88a2b6ac7)

## Result
Thus, the program is successfully executed
