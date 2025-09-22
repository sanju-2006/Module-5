# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
class Student:
    def __init__(self, name):
        print("Inside Constructor")
        print("Object initialized")
        self.name = name
        print(f"Hello, my name is {self.name}")

    def __del__(self):
        print("Inside destructor")
        print("Object destroyed")

s = Student("Emma")
del s
```

### OUTPUT

Inside Constructor
Object initialized
Hello, my name is Emma
Inside destructor
Object destroyed

### RESULT

<img width="549" height="235" alt="image" src="https://github.com/user-attachments/assets/4dabfe64-7ed6-47c6-bca0-c28cd23aa6f5" />
