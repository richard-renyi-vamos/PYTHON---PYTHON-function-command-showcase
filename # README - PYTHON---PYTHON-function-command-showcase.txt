CHATGPT CONVERSATION

****************

You said:
create a PYTHON code that showcases most basic functions & commands of python
ChatGPT said:
Here's a Python script that demonstrates basic functions and commands, covering variables, data types, loops, conditionals, functions, and file handling.


Answer in chat instead
This script covers basic Python concepts, making it a great reference for beginners. Let me know if you want to expand on any section! 🚀🐍


****************

# Basic Python Functions & Commands

# 1. Printing to the console
print("Hello, World!")

# 2. Variables & Data Types
name = "Richard"  # String
age = 30  # Integer
height = 1.75  # Float
is_student = False  # Boolean

# 3. Lists (Arrays)
numbers = [1, 2, 3, 4, 5]
print(numbers[2])  # Accessing elements
numbers.append(6)  # Adding elements
print(numbers)

# 4. Dictionaries (Key-Value Pairs)
person = {"name": "Richard", "age": 30, "city": "Budapest"}
print(person["name"])
person["job"] = "Business Analyst"  # Adding a new key-value pair
print(person)

# 5. Conditional Statements
if age > 18:
    print("You are an adult.")
else:
    print("You are a minor.")

# 6. Loops
# For loop
for num in numbers:
    print(num)

# While loop
count = 0
while count < 3:
    print("Count is:", count)
    count += 1

# 7. Functions
def greet(name):
    return "Hello, " + name + "!"

print(greet("Richard"))

# 8. Classes & Objects
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    
    def introduce(self):
        return f"My name is {self.name} and I am {self.age} years old."

person1 = Person("Richard", 30)
print(person1.introduce())

# 9. Exception Handling
try:
    result = 10 / 0  # This will cause a ZeroDivisionError
except ZeroDivisionError:
    print("You cannot divide by zero!")

# 10. File Handling
with open("example.txt", "w") as file:
    file.write("This is a test file.")

with open("example.txt", "r") as file:
    content = file.read()
    print(content)




