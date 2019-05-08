#calculator

number1 = input("Enter a number: ")
operation = input("Which operation would you like to do? ")
number2 = input("Enter a second number: ")

number1: int = int(number1)
number2: int = int(number2)

if operation == "+":
    result = number1 + number2
elif operation == "-":
    result = number1 - number2
elif operation == "%":
    result = number1 % number2
elif operation == "/":
    if number2 == 0:
        print("Naughty, naughty ... better don't do that again ;)")
        result = "undefined"
    else:
        result = number1 / number2
elif operation == "*":
    result = number1 * number2
else:
    print("I don't know this operation ... yet!")

result = str(result)

print ("I think the result might be " + result)
