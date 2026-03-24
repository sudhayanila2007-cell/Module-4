# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
class Circle:
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        pi = 3.14
        return pi * self.radius * self.radius


# Create object
r = float(input("Enter radius: "))
c = Circle(r)

# Calculate and print area
print("Area of Circle:", c.area())
```

## Output
```
Enter radius: 5
Area of Circle: 78.5
```
## Result
the code is verified.
