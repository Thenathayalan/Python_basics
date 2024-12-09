### User Input

Getting input from user is the most important thing in Programming

```
#python user input

Name = input("Enter Name : ")
print(Name)

Age = int(input("Enter Age : "))
print(Age)

Rating = float(input("Enter Rating : "))
print(Rating)
```
### Multiple Inputs
Some times we need to get multiple inputs in single line like space separated so we use `split()` function to get the job done
```
nums = input("Enter two numbers : ")
a, b = nums.split(" ") # Here we need to separate input inbetween spaces
print("a value:", a, "b value:", b)
```
### Value Error
```
Temp = int(input("Enter Temperature : "))

print("Given Temperature :", Temp)
```
 Run the above code and give a temperature value as floating point like **34.5, 55.5, 70.8** and run the code
 ```
Enter Temperature : 25.2
Traceback (most recent call last):
  File "/media/thenathayalan/69A89B5E33FBE3D8/Program_files/python/Code_IO/test.py", line 1, in <module>
    Temp = int(input("Enter Temperature : "))
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
ValueError: invalid literal for int() with base 10: '25.2'
```
- Boom you will get a **Value Error** because we are using **Int** datatype for a variable Temp and giving **Float** datatype as input
- Whenever **Value Error** arises in your code you need to **check** the variable **data types**
### Outputs in python
We use `print()` command to display output to the terminal
```
date = 18
month = 11
year = 2003

print(date, month, year ,sep='-')

print("*****", end='')
print("****")

```