# Exp.No:27  
## Operator Overloading

---

### AIM  
To write a Python program to compute the product of two complex numbers by overloading the binary '+' operator using a class named complex.

---

### ALGORITHM

Define a Class:

Create a class named complex to represent complex numbers with real and imaginary parts.

Constructor (init):

Initialize two instance variables, a for the real part and b for the imaginary part.

Overload the + Operator:

Define the add method to overload the + operator.

Instead of addition, perform multiplication of the complex numbers using the formula:

( 𝑎 + 𝑏 𝑖 ) ⋅ ( 𝑐 + 𝑑 𝑖 )
( 𝑎 𝑐 − 𝑏 𝑑 ) + ( 𝑎 𝑑 + 𝑏 𝑐 ) 𝑖 (a+bi)⋅(c+di)=(ac−bd)+(ad+bc)i Create Objects:

Create two instances of the complex class with required real and imaginary parts.

Perform Operation:

Use the overloaded + operator to compute the product and display the result.
---

### PROGRAM

class complex:

   def __init__(self, a, b):
   
   self.a = a
    self.b = b
    
  
 def __add__(self, other):
 
 return self.a * other.a, self.b * other.b
 
Ob1 = complex(1, 2)

Ob2 = complex(2, 3)

Ob3 = Ob1 + Ob2

print(Ob3)

### OUTPUT

![image](https://github.com/user-attachments/assets/355dd52f-d307-49a2-85a8-19a5395f7149)

### RESULT

Thus the python program was initiated and executed successfully.
