# Exp.No:29  
## Encapsulation


### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.


### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**



### PROGRAM

```
class Student:
    def __init__(self, name, age):
        # private member
        self.__name = name
        self.__age = age
    def get_name(self):
        return self.__name
    def get_age(self):
        return self.__age
    def set_age(self,age):
        self.__age = age       


stud = Student('Jessa', 14)
print('Name:', stud.get_name(), stud.get_age())
stud.set_age(16)
print('Name:', stud.get_name(), stud.get_age())

```

### OUTPUT
![image](https://github.com/user-attachments/assets/0ca3d8e7-aa58-4035-ac1d-684903d0bddd)



### RESULT
Thus the  Python program to create a class `Student` with the private members `name` and `age` is implemented and executed successfully.


