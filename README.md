# Code_Challenge4.py
print("Welcome to the Arithmetic Operations Program!")

num1 = eval(input("Please enter the first number: "))
num2 = eval(input("Please enter the second number: "))

add_answer = num1 + num2
subtract_answer = num1 - num2
multiply_answer = num1 * num2
divide_answer = num1 / num2
fdivide_answer = num1 // num2
remainder_answer = num1 % num2
quotient_answer = num1 / num2
exponent_answer = num1 ** num2

print(f"\nGreat! Here are the results for the numbers {num1} and {num2}:")
print(f"The sum of {num1} and {num2} is {add_answer}")
print(f"The difference of {num1} and {num2} is {subtract_answer}")
print(f"The product of {num1} and {num2} is {multiply_answer}")
print(f"The division of {num1} by {num2} is {divide_answer}")
print(f"The floor division of {num1} by {num2} is {fdivide_answer}")
print(f"The remainder of {num1} divided by {num2} is {remainder_answer}")
print(f"The quotient of {num1} divided by {num2} is {quotient_answer}")
print(f"The exponent of {num1} to the power of {num2} is {exponent_answer}")

print("\nThank you for using the Arithmetic Operations Program! Have a great day!")
