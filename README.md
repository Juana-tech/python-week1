print("1 - Add")
print("1 - Subtract")
print("1 - Multiply")
print("1 - Divide")
option =int(input("Choose an operation"))

if(option in[1,2,3,4]):
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))

    if(option == 1):
        result = num1 + num2
    elif(option == 2):
        result = num1 - num2
    elif(option == 3):
        result = num1 * num2
    elif(option == 4):
        result = num1 / num2
    
    else:
        print("Invalid operation entered")

        print("The result of the operation is{}".format(result))
