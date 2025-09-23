# Exp.No:23  
## Multiple Inheritance

---

### AIM  
Write a Python program to get the name, attendance and Id of a student and check they are eligible for exam using multiple inheritance

Note: attendance >75 eligible student else Not Eligible student

---

### ALGORITHM

1. Define the `Student` class.
2. Inside the `Student` class, define the `__init__` method (constructor). The `__init__` method accepts two parameters: `name` and `student_id`.
    - Inside the `__init__` method: Assign the value of `name` to `self.name` and `student_id` to `self.student_id`.
3. Define the `get_student_info` method inside the `Student` class:
    - This method should return a string formatted with `self.name` and `self.student_id`.
4. Define the `Attendance` class, which inherits from the `Student` class.
5. Inside the `Attendance` class, define the `__init__` method (constructor).
    - The `__init__` method accepts three parameters: `name`, `student_id`, and `attendance`.
    - Inside the `__init__` method: Call the parent class constructor `super().__init__(name, student_id)` to initialize `name` and `student_id`. Assign the value of `attendance` to `self.attendance`.
6. Define the `check_eligibility` method inside the `Attendance` class:
    - If `self.attendance` is greater than 80, return a formatted string indicating the student is eligible for the module exam.
    - Otherwise, return a formatted string indicating the student is not eligible for the module exam.
7. Prompt the user to enter the `name` (as a string), `student_id` (as an integer), and `attendance` (as an integer).
8. Create an instance `student` of the `Attendance` class, passing the entered `name`, `student_id`, and `attendance` to the constructor.
9. Call the `check_eligibility` method on the `student` object and print the result.
10. Terminate the program.

---

### PROGRAM

```
class sec:
    def __init__(self):
        self.name=name
        self.age=age
        self.id=id
class cse(sec):
    def res(self):
        print(name)
        print(age)
        if(id>80):
            print("Eligible for Exam")
        else:
            print("Not Eligible for Exam")
name=input()
age=int(input())
id=int(input())
obj=cse()
obj.res()
```

### OUTPUT

<img width="606" height="278" alt="image" src="https://github.com/user-attachments/assets/1f5ecf12-a846-4ee0-aa31-5e66346f159a" />


### RESULT

Python program to get the name, attendance and Id of a student and check they are eligible for exam using multiple inheritance is successfully verified



