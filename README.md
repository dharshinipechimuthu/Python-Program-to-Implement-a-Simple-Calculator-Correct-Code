# Python-Program-to-Implement-a-Simple-Calculator-Correct-Code
def add(x, y):
    print("Result:", x + y)

def subtract(x, y):
    print("Result:", x - y)

def multiply(x, y):
    print("Result:", x * y)

def divide(x, y):
    print("Result:", x / y)

print("Enter two numbers")
n1 = int(input())
n2 = int(input())

print("Enter the operation (+, -, *, /)")
op = input()

if op == '+':
    add(n1, n2)
elif op == '-':
    subtract(n1, n2)
elif op == '*':
    multiply(n1, n2)
elif op == '/':
    divide(n1, n2)
else:
    print("Invalid entry")

Output:
Enter two numbers
10
5
Enter the operation (+, -, *, /)
*
Result: 50
