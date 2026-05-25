# 🧮 Datatypes-Complex Number Creation in Python

## 🎯 Aim
To write a Python program that reads two integers, creates a complex number using them, and then prints the complex number along with its real and imaginary parts.

## 🧠 Algorithm
1. Read an integer input from the user and assign it to the variable `a` (real part).
2. Read another integer input from the user and assign it to the variable `b` (imaginary part).
3. Create a complex number `x` using the `complex(a, b)` function.
4. Print the complex number `x`.
5. Print the real part of `x` using `x.real`.
6. Print the imaginary part of `x` using `x.imag`.

## 💻 Program
a = int(input("Enter first integer: "))
b = int(input("Enter second integer: "))

c = complex(a, b)

print("Complex number =", c)
print("Real part =", c.real)
print("Imaginary part =", c.imag)

## Output
Enter first integer: 4
Enter second integer: 5
Complex number = (4+5j)
Real part = 4.0
Imaginary part = 5.0

## Result
The program reads two integers, creates a complex number using them, and prints the complex number along with its real and imaginary parts.
