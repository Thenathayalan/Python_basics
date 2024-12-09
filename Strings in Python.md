### Strings
Strings in python are surrounded by either single quotation marks, or double quotation marks.

**'hello'** is the same as **"hello"**.

You can display a string literal with the `print()` function
```
print("Hello")  
print('Hello')
```
### Quotes Inside Quotes
You can use quotes inside a string, as long as they don't match the quotes surrounding the string
```
print("It's alright")  
print("He is called 'Johnny'")  
print('He is called "Johnny"')

# Assign String to a Variable
a = "Hello"  
print(a)
```
### Multi-line Strings
You can assign a multi-line string to a variable by using three quotes
```
a = """Lorem ipsum dolor sit amet,  
consectetur adipiscing elit,  
sed do eiusmod tempor incididunt  
ut labore et dolore magna aliqua."""  
print(a)

b = '''Lorem ipsum dolor sit amet,  
consectetur adipiscing elit,  
sed do eiusmod tempor incididunt  
ut labore et dolore magna aliqua.'''  
print(b)

# Single quotes or double quotes both did the same job for us.
```
### length function
`len()` is used to return the length of the given string
```
str1 = "python"
print(len(str1))

str2 = "Aww some"
print(len(str2)) # Open your eyes
```
### Slicing Strings
You can return a range of characters by using the slice syntax.

Specify the **start index** and the **end index**, separated by a **colon**, to return a part of the string
|k|a|i|l|a|s|h|
|-|-|-|-|-|-|-|
|0|1|2|3|4|5|6|
|-7|-6|-5|-4|-3|-2|-1|
```
# String index
a = "Kailash"
print(a[:3]) # Slice From the Start
print(a[3:]) # Slice To the End
print(a[0]) # Get first character
print(a[6]) # Get last character

# String Slicing

print(a[::-1])
print(a[::2])

print(a[3:7]) # Note end index not included
print(a[3:7:1])
print(a[6:2:-1])

# Negative Indexing
print(a[-4:0]) # Note end index not included
print(a[-4:])
```
### Other String functions
- Upper case
- Lower case
- Remove White-space
- Replace String
- Split String [etc...](https://www.w3schools.com/python/python_strings_methods.asp)
```
a = "Hello, World!"  
print(a.upper())

a = "Hello, World!"
print(a.lower())

a = " Hello, World! "  
print(a.strip()) # returns "Hello, World!"

a = "Hello, World!"  
print(a.replace("H", "J"))

a = "Hello, World!"  
print(a.split(",")) # returns ['Hello', ' World!']
```