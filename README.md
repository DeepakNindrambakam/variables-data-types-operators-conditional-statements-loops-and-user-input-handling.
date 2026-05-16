# variables-data-types-operators-conditional-statements-loops-and-user-input-handling.
Python programs demonstrating variables, data types, operators, conditional statements, loops, and user input handling.
#variables and data types

name = "Deepak"      # String
age = 20             # Integer
height = 5.8         # Float
is_student = True    # Boolean

print("Name:", name)
print("Age:", age)
print("Height:", height)
print("Student:", is_student)
# Arithmetic Operators

a = 10
b = 5

print("Addition:", a + b)
print("Subtraction:", a - b)
print("Multiplication:", a * b)
print("Division:", a / b)
print("Modulus:", a % b)
# Check whether number is positive, negative, or zero

num = int(input("Enter a number: "))

if num > 0:
    print("Positive Number")
elif num < 0:
    print("Negative Number")
else:
    print("Zero")
    # Even or Odd

num = int(input("Enter a number: "))

if num % 2 == 0:
    print("Even Number")
else:
    print("Odd Number")
    # Print numbers from 1 to 10

for i in range(1, 11):
    print(i)
    # Sum of first 5 numbers

i = 1
total = 0

while i <= 5:
    total = total + i
    i = i + 1

print("Sum =", total)
# Multiplication Table

num = int(input("Enter a number: "))

for i in range(1, 11):
    print(num, "x", i, "=", num * i)
    # Simple Calculator

num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))

print("Addition =", num1 + num2)
print("Subtraction =", num1 - num2)
print("Multiplication =", num1 * num2)

if num2 != 0:
    print("Division =", num1 / num2)
else:
    print("Cannot divide by zero")
    # Factorial Program

num = int(input("Enter a number: "))

fact = 1

for i in range(1, num + 1):
    fact = fact * i

print("Factorial =", fact)
# Largest among three numbers

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a > b and a > c:
    print("Largest number is", a)
elif b > c:
    print("Largest number is", b)
else:
    print("Largest number is", c)
