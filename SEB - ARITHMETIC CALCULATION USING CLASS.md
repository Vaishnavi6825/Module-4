# Exp.No:20
## SEB - ARITHMETIC CALCULATION USING CLASS
# AIM
To write a Python program to perform addition and division operations using a class. The class should be named Saveetha, and the function names should be setvalues (to set a and b values), add, and div. The program should handle the following cases:

choice 1 → Perform addition

choice 2 → Perform division

choice 0 → Exit

For other choices, print 'Invalid choice'
# ALGORITHM
1.Begin the program.

2.Create a class Saveetha.

3.Define the following methods inside the Saveetha class:
__init__(self): Initializes a and b to zero.

4.setvalues(self, a, b): Sets the values of a and b.

5.add(self): Performs the addition operation.

6.div(self): Performs the division operation. If b is zero, returns an error message for division by zero.

7.Create a main() function.

8.Take input from the user for the values of a and b using setvalues(a, b) method.

9.Use a while True loop to repeatedly ask the user for a choice:
If the choice is 1, call the add() method and print the result.

10.If the choice is 2, call the div() method and print the result. Handle division by zero.

11.If the choice is 0, print "Exiting!" and exit the loop.

12.If the choice is not 1, 2, or 0, print "Invalid choice".

13.Terminate the program.
# PROGRAM
```
# REGNO:-212222060121
#Name:-Kiruthika M 
    def __init__(self):
        self.a = 0
        self.b = 0

    def setvalues(self, a, b):
        self.a = a
        self.b = b

    def add(self):
        return self.a + self.b

    def div(self):
        if self.b != 0:
            return self.a / self.b
        else:
            return "Error: Division by zero"
def main():
    saveetha_obj = Saveetha()
    a = float(input())``
    b = float(input())
    while True:
        saveetha_obj.setvalues(a, b)
        choice = int(input())
        if choice == 1:
            result = saveetha_obj.add()
            print(f"Result:  {int(result)}")
        elif choice == 2:
            result = saveetha_obj.div()
            print(f"Result:  {int(result)}")
        elif choice == 0:
            print("Exiting!")
            break
        else:
            print("Invalid choice")

# Run the main function
main()
```


# OUTPUT
<img width="1011" height="456" alt="image" src="https://github.com/user-attachments/assets/5f716e34-0bd4-401b-a485-cc66108329f2" />

# Result
Thus the arithmetic calculation using class has been implemented and executed successfully.



