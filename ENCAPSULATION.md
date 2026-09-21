# Exp.No:29 Encapsulation
# AIM
To write a Python program to create a class Student with the private members name and age, and add getter and setter methods to initialize and modify the age variable.

# ALGORITHM
Start the Program. Define the Student class. Inside the Student class, define the init method to initialize name and the private member __age. Define a getter method get_age to return the value of the private member __age. Define a setter method set_age to set a new value to the private member __age. Create an object stud of the Student class with the name 'Jessa' and age 14. Print the name and the age of stud using the getter method. Use the setter method set_age to change the age of stud to 16. Print the name and the updated age of stud using the getter method. End the program.

# PROGRAM
~~~
Reg - 212222060245 Name - Singamala Rakshitha

class Student:
    def __init__(self, name, roll_no, age):
        self.name = name
        self.__roll_no = roll_no   # private variable
        self.__age = age           # private variable

    def show(self):
        print('Student Details:', self.name, self.__roll_no)

    def get_roll_no(self):        # getter method
        return self.__roll_no

    def set_roll_no(self, number):  # setter method
        if number > 50:
            print('Invalid roll no. Please set correct roll number')
        else:
            self.__roll_no = number


# Create an object
jessa = Student('Jessa', 10, 15)

jessa.show()           # prints current details
jessa.set_roll_no(52)  # tries to set roll_no = 52 (invalid)
jessa.set_roll_no(25)  # sets roll_no = 25 (valid)
jessa.show()           # prints updated details
~~~
# OUTPUT
<img width="947" height="221" alt="image" src="https://github.com/user-attachments/assets/2d397b43-429f-4386-870d-75a9392049cc" />

# RESULT
Thus the program to create class with private members and add getter and setter methods to initialize and modify the given variable has been implemented and executed successfully.
