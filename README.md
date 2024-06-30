# PYTHON Source Code for Generating Fibonacci Series

def fib(n):
    print(0)
    print(1)
    n1 = 0
    n2 = 1
    ctr = 2
    while ctr<n and ctr>1:
        f = n1+n2
        print(f)
        n1, n2 = n2, f
        ctr+=1

        return fib
x = int(input("Enter a Number: "))
fib(x)
