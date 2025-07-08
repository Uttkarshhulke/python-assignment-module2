def factorial(n):
    if n == 0 or n == 1:
        return 1
    else:
        return n * factorial(n - 1)
x=4
result = factorial(x)

print("The factorial of",x,"is:",result)


output:
The factorial of 4 is: 24