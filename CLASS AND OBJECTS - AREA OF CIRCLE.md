## CLASS AND OBJECTS - AREA OF CIRCLE
# AIM
To write a Python program to take the radius from the user and find the area of a circle using the class name umbrella and function name rain.

# ALGORITHM
1.Begin the program.

2.Create a class named umbrella.

3.Define a method rain(self, r) inside the class umbrella that accepts a radius r as an argument.

4.Inside the rain method

5.Calculate the area of a circle using the formula:
[ \text{Area} = \pi \times r^2 ]

6.Use the math.pi constant to get the value of π and perform the calculation.

7.Print the result, formatted to two decimal places.

8.Prompt the user for an integer input to represent the radius of the circle.

9.Create an instance of the umbrella class and store it in the variable u.

10.Call the rain method of the umbrella class, passing the user-provided radius r as an argument.

11.Terminate the program.

# PROGRAM
```
# REGNO:-212222060121
# Name:-Kiruthika M
import math
class umbrella:
    def rain(self,r):
        res=math.pi * r * r
        print(f"Area of circle: {res:.2f}")
r=int(input())
u=umbrella()
u.rain(r)
```

# OUTPUT
<img width="1011" height="215" alt="image" src="https://github.com/user-attachments/assets/30886f81-5be0-4da7-b6ed-b703b1e39afd" />


# RESULT
Thus the python program for calculating the area of a circle was implemented and executed successfully.
