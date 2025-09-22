# Exp.No:25  
## Hierarchical Inheritance

---

### AIM  
To write a Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor`.

---

### ALGORITHM

1. **Begin the program.**
2. **Create a class Details** with an `__init__` method to initialize three attributes: `id`, `name`, and `gender`.
3. **Define a method display_details()** to print the values of `id`, `name`, and `gender`.
4. **Create a class Employee** that inherits from the `Details` class. 
   - Add two additional attributes: `company` and `department`.
   - Override the `display_details()` method to print the employee-specific attributes (`company` and `department`) along with the inherited details.
5. **Create a class Doctor** that also inherits from the `Details` class. 
   - Add two additional attributes: `hospital` and `department`.
   - Override the `display_details()` method to print the doctor-specific attributes (`hospital` and `department`) along with the inherited details.
6. **Accept input** for employee and doctor details.
7. **Create objects of Employee and Doctor** using the input.
8. **Call the `display_details()` method** for both objects to print the details.
9. **Terminate the program.**

---

### PROGRAM
```
class Details:
    def get_common(self):
        self.id = int(input())
        self.name = input()
        self.gender = input()

class Employee(Details):
    def get_employee(self):
        self.company = input()
        self.dept = input()

    def display_employee(self):
        print("Employee Object")
        print("Id: ", self.id)
        print("Name: ", self.name)
        print("Gender: ", self.gender)
        print("Company: ", self.company)
        print("Department: ", self.dept)

class Doctor(Details):
    def get_doctor(self):
        self.hospital = input()
        self.dept = input()

    def display_doctor(self):
        print("\nDoctor Object")
        print("Id: ", self.id)
        print("Name: ", self.name)
        print("Gender: ", self.gender)
        print("Hospital: ", self.hospital)
        print("Department: ", self.dept)

e = Employee()
e.get_common()
e.get_employee()
e.display_employee()

d = Doctor()
d.get_common()
d.get_doctor()
d.display_doctor()


```

### OUTPUT  

Employee Object
Id:  1
Name:  sharma
Gender:  male
Company:  Tata
Department:  pharma

Doctor Object
Id:  12
Name:  revathi
Gender:  female
Hospital:  aims
Department:  ENT


### RESULT


<img width="562" height="435" alt="image" src="https://github.com/user-attachments/assets/187b4c58-6d58-4ff4-a45a-679557b17b16" />
