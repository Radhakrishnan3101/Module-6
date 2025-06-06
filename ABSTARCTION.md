# Exp.No:28  
## Abstraction

---

### AIM  
To write a Python program to define the abstract base class named `Polygon` and also define the abstract method. This base class is inherited by various subclasses. Implement the abstract method in each subclass. Create objects of the subclasses and invoke the `sides()` method.

---

### ALGORITHM

Import Required Module:

Import ABC and abstractmethod from the abc module.

Define Abstract Base Class:

Create a class Animal which inherits from ABC.

Define an abstract method sound() using the @abstractmethod decorator.

Define a concrete method sleep() that prints a generic message, which will be inherited by all child classes.

Create Child Classes:

Define multiple child classes such as Cat, Snake, Dog, and Lion which inherit from Animal.

In each subclass, implement the sound() method with a message specific to that animal.

Demonstrate Functionality:

Call the sleep() method.

Create instances of the child classes.

Call the sound() method on each instance to display the unique behavior of each animal.

---

### PROGRAM

from abc import ABC,abstractmethod
 
class Animal(ABC):

   @abstractmethod
   
   def sound(self):
   
 pass
    
 class Snake(Animal):
 
   def sound(self):
   
   print("I can hiss")
 
class Dog(Animal):

   def sound(self):
   
   print("I can bark")
 
class Lion(Animal):

   def sound(self):
   
   print("I can roar")
       
class Cat(Animal):

   def sound(self):
   
   print("I can meow")
        
print("I am going to sleep in a while")
        
c = Cat()

c.sound()

s = Snake()

s.sound()


### OUTPUT
![image](https://github.com/user-attachments/assets/1665a312-f335-43e3-9b6b-5bb9b3473160)


### RESULT
Thus the python program was initiated and executed successfully.
