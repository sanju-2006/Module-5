# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

```
class Multiply:
    def __init__(self,x,y):
        self.x=x
        self.y=y
    def calculate(self):
        self.total = self.x * self.y
    def display(self):
        print('ele 1 = {} '.format(self.x))
        print('ele 2 = {} '.format(self.y))
        print('Total  = {} '.format(self.total))

x=int(input())
y=int(input())
obj = Multiply(x,y)
obj.calculate()
obj.display()
```

### OUTPUT

ele 1 = 5
ele 2 = 6
Total  = 30

### RESULT


<img width="426" height="279" alt="image" src="https://github.com/user-attachments/assets/51a1b963-983a-4999-8166-61ec1b5d8697" />
