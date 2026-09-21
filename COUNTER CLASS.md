# Exp.No:30 COUNTER CLASS
# AIM
To write a Python program to create a Counter class that can increment the value of a counter.

# ALGORITHM
Start the Program. Define the Counter class. Initialize the current variable with 0. Define the increment() method to increment the value of current by 1. Define the value() method to return the current value of current. Define the reset() method to reset the current value back to 0. Create a counter object of the Counter class. Call the increment() method three times to increment the counter. Call the value() method and print the result to show the current counter value. End the program.

# PROGRAM
~~~
Reg - 212222060245 Name -Singamala Rakshitha

class Counter:
    def __init__(self):   # constructor (initializes object attributes)
        self.current = 0

    def increment(self):  # increases counter value by 1
        self.current += 1

    def value(self):      # returns the current counter value
        return self.current

    def reset(self):      # resets counter back to 0
        self.current = 0


counter = Counter()      # create a new Counter object
counter.increment()      # now current = 1
counter.increment()      # now current = 2
counter.increment()      # now current = 3

print(counter.value())   # prints 3
~~~
# OUTPUT
<img width="652" height="162" alt="image" src="https://github.com/user-attachments/assets/a4eadb28-b419-43fa-a270-ed72bf0330ad" />


# RESULT
Thus the program to create a class that can increment the value of a counter has been implemented and executed successfully.
