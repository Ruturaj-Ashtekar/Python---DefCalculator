# Python---DefCalculator
This is a basic calculator built in Python vary basic and upgradation will be done in this Calculator

starting :

def Calculator(num1,method,num2):
    if "+" in method:
        a = (f"{num1} + {num2} = {num1+num2}")
        return a
    elif "-" in method :
        b = (f"{num1} - {num2} = {num1-num2}")
        return b
    elif "x" in method :
        c = (f"{num1} X {num2} = {num1*num2}")
        return c
    elif "/" in method :
        d = (f"{num1} / {num2} = {num1/num2}")
        return d

 
num1 = int(input(''))
method = input('')
num2 = int(input(''))

calculate = Calculator(num1,method,num2)
print(calculate)

ending.
