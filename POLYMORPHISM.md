# Exp.No:30  
## POLYMORPHISM


### AIM  
To demonstrate polymorphism in Python using two independent classes with the same method names and executing them through iteration.

### ALGORITHM

1.Define class Tiger with methods nature() and color().
2.Define class Elephant with the same method names nature() and color().
3.Create instances of both classes.
4.Pack the objects into a tuple.
5.Iterate through the tuple using a loop.
6.Call nature() and color() on each object.

### PROGRAM

```
class Tiger:
    def nature(self):
        print("I am a Tiger and I am dangerous.")

    def color(self):
        print("Tigers are orange with black strips")

class Elephant:
    def nature(self):
        print("I am an Elephant and I am calm and harmless")
        
    def color(self):
        print("Elephants are grayish black")
    
obj1 = Tiger()
obj2 = Elephant()

obj1.nature()
obj1.color()
obj2.nature()
obj2.color()


```

### OUTPUT
![image](https://github.com/user-attachments/assets/abb9d348-733c-4e51-8bd3-f1ecaf673d5e)


### RESULT
Thus the python program using polymorphism is implemented and executed successfully.
