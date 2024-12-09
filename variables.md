Variables are containers for storing data values.
### Creating Variables
A variable is created the moment you first assign a value to it.
```
a = 4  # a is of type int
b = 10.50  # b is of type float
c = "Sally"  # c is of type str
d = True  # d is of type bool

print(a, b, c, d)

print(type(a), type(b), type(c), type(d))
```
### Type Casting
Converting one datatype to other datatype
```
a = str("4")  # a is of type str
b = int(a)  # b is of type int
c = float(b)  # c is of type float

print(a, b, c)

print(type(a), type(b), type(c))
```
### Case-Sensitive
Variable names are case-sensitive.
```
a = 4  
A = "Sally"  

print(a, A)
```
### Variable Names
A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume). Rules for Python variables:

- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)
- A variable name cannot be any of the Python keywords
```
# Legal variable names:

myvar = "John"  
my_var = "John"  
_my_var = "John"  
myVar = "John"  
MYVAR = "John"  
myvar2 = "John"

# Illegal variable names:

2myvar = "John"  
my-var = "John"  
my var = "John"
```
## Many Values to Multiple Variables
Python allows you to assign values to multiple variables in one line:
```
x, y, z = "Orange", "Banana", "Cherry"  
print(x)  
print(y)  
print(z)
```
## One Value to Multiple Variables
And you can assign the _same_ value to multiple variables in one line:
```
x = y = z = "Orange"  
print(x)  
print(y)  
print(z)
```