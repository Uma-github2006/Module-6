# Exp.No:28  
## Abstraction

### AIM  
To implement abstraction using an abstract class and demonstrate method overriding through inheritance.


### ALGORITHM

1.Define an Abstract Class Bank:
   Import ABC and abstractmethod from the abc module.
   Define an abstract class Bank that inherits from ABC (abstract base class).
   Define an abstract method bank_info() which is not implemented in the Bank class (it is only defined).
   Optionally, define a concrete method interest() which provides a default implementation.
2.Define a Subclass SBI that Inherits from Bank:
   Create a subclass SBI that inherits from the abstract class Bank.
   Implement the bank_info() method in the SBI class (providing specific information related to the bank).
   Implement the interest() method in the SBI class to provide the interest rate specific to the bank.
3.Create an Object of SBI:
   Create an instance of the SBI class and call the implemented methods bank_info() and interest() to display the respective information.
4.Run the Program:
   When the object is created, the program will display the bank information and the interest rate specific to SBI.


### PROGRAM

```
from abc import ABC, abstractmethod

#Abstract Class
class Bank(ABC):
    
    
    @abstractmethod
    def bank_info(self):
        pass
  
    def interest(self):
        pass
   
class SBI(Bank):
    
    def bank_info(self):
         print("Welcome to bank")

    def interest(self):
        print("In sbi bank 5 rupees interest")
       

s=SBI()
s.bank_info()
s.interest()

```

### OUTPUT
![image](https://github.com/user-attachments/assets/f74034ee-0db5-40ed-bf5f-d3ac4ec11628)



### RESULT
Thus the abstract class Bank is implemented and executed successfully.
