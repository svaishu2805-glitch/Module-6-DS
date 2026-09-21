# Exp.No:26 Method Overriding
# AIM
To write a Python program to create a Parent class Bird and inherit two child classes Sparrow and Ostrich from the Bird class with the same method flight(). Create an object for each class and call the methods of the class which will print the name of the bird that is flying.

# ALGORITHM
Begin the program. Define the Bird class: Create a method intro() to print "There are many types of birds." Create a method flight() to print "Most of the birds can fly but some cannot." Define the Sparrow class, which inherits from Bird: Override the flight() method. Call the intro() method from the parent class. Print "Sparrows can fly." Define the Ostrich class, which inherits from Bird: Override the flight() method. Call the intro() method from the parent class. Print "Ostriches cannot fly." Create an object obj_bird of the Bird class. Create an object obj_spr of the Sparrow class. Create an object obj_ost of the Ostrich class. Print the general message "There are many types of birds." Call the flight() method on each object (obj_bird, obj_spr, obj_ost) to display the respective messages. Terminate the program.

# PROGRAM
~~~
Reg - 212222060245 Name - Singamala Rakshitha

class Bird:
    def intro(self):
        print("There are many types of birds.")

    def flight(self):
        print("Most of the birds can fly but some cannot.")


class sparrow(Bird):   # inherits from Bird
    def flight(self):  # overrides the flight() method
        print("Sparrows can fly.")


class ostrich(Bird):   # inherits from Bird
    def flight(self):  # overrides the flight() method
        print("Ostriches cannot fly.")


# Objects
bird = Bird()
spr = sparrow()
ost = ostrich()

bird.intro()   # call Bird's intro()
bird.flight()  # call Bird's flight()
spr.intro()    # inherited from Bird
spr.flight()   # overridden in sparrow
bird.intro()   # Bird's intro again
ost.flight()   # overridden in ostrich
~~~
# OUTPUT
<img width="826" height="269" alt="image" src="https://github.com/user-attachments/assets/b1dc3f2c-695c-46af-82a2-f513635cc85a" />

# RESULT
Thus the program to create a Parent class and inherit two child classes from the class with the same method has been implemented and executed successfully.
