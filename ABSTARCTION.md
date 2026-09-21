# Exp.No:28 Abstraction
# AIM
To write a Python program to define the abstract base class named Polygon and also define the abstract method. This base class is inherited by various subclasses. Implement the abstract method in each subclass. Create objects of the subclasses and invoke the sides() method.

# ALGORITHM
Start the Program. Import the ABC class from the abc module to implement abstraction. Define the abstract base class Polygon: Inherit from ABC (Abstract Base Class). Define an abstract method sides() with no implementation. Define the Triangle class that inherits from Polygon: Implement the sides() method to print "Triangle has 3 sides". Define the Pentagon class that inherits from Polygon: Implement the sides() method to print "Pentagon has 5 sides". Define the Hexagon class that inherits from Polygon: Implement the sides() method to print "Hexagon has 6 sides". Define the Square class that inherits from Polygon: Implement the sides() method to print "I have 4 sides". Create an object t of the Triangle class and call the sides() method to print the number of sides. Create an object s of the Square class and call the sides() method to print the number of sides. Create an object p of the Pentagon class and call the sides() method to print the number of sides. Create an object k of the Hexagon class and call the sides() method to print the number of sides. End the Program.

# PROGRAM
~~~
Reg-212222060245 Name-Singamala Rakshitha

from abc import ABC  
  
class Polygon(ABC):   
  
   # abstract method   
   def sides(self):   
      pass  
  
class Triangle(Polygon):   
  
     
   def sides(self):   
      print("Triangle has 3 sides")   
  
class Pentagon(Polygon):   
    def sides(self):
        print("Pentagon has 5 sides")
   #Add code here
class Hexagon(Polygon):  
    def sides(self):
        print("Hexagon has 6 sides")
  
   #Add your code
class square(Polygon):   
  
   def sides(self):   
      print("I have 4 sides")   
  
# Driver code   
t = Triangle()   
s = square()  
p = Pentagon()   
k = Hexagon()   
t.sides ()
s.sides ()
p.sides ()
k.sides ()
~~~
# OUTPUT
<img width="1210" height="270" alt="image" src="https://github.com/user-attachments/assets/f377d8a1-1168-4322-ae74-df9c858f57aa" />

# RESULT
Thus the program to define the abstract base class and also define the abstract method has been implemented and executed successfully.
