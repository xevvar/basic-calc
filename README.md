# basic-calc

num1 = float(input("Enter a number: "))
op = input("Enter an operator: ")
num2 = float(input("enter a number: "))

if op == "+":
    print(num1 + num2)
elif op == '-':
    print(num1 - num2)
elif op == '/':
    print(num1 / num2)
elif op == "*":
    print(num1 * num2)
else:
    print("invalid operator")

