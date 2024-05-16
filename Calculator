#First program, let's see where this goes.

'''
I think I've decided to attempt to make a calculator,
potentially a scientific one.
'''

import math


# -------------------- VERSION 2 OF THE CALCULATOR --------------------

def myCalculator():
    print("Welcome to the CALCULATOR\n")



    num123 = input("Enter any key to begin. ")
    print("When you're done enter 'Exit' to stop.\n")

    while True:
        try:
            num = str(input("Enter a number: "))
            if num != str("Exit"):
                num = float(num)
            else:
                break
            print("The entered number is:", num)
        except ValueError:
            print("Invalid input. Please enter a number.")
        else:
            break
            
    operationsKey = True
    while operationsKey == True:

        if num != str("Exit"):
            num = float(num)
        else:
            break

        operator = str(input("Enter an operator: "))
            
        if operator == "+":
            key = True
        elif operator == "-":
            key = True
        elif operator == "*":
            key = True
        elif operator == "/":
            key = True
        elif operator == "Exit":
            break
        else:
            key = False

        while key == False:
        
            operator = input("Invalid input. Please enter an operator(+,-,*,/): ")
            print(operator)

            if operator == "+":
                key = True
            elif operator == "-":
                key = True
            elif operator == "*":
                key = True
            elif operator == "/":
                key = True
            else:
                key = False


        while True:
            try:
                num2 = str(input("Enter the next number: "))
                if num2 != str("Exit"):
                    num2 = float(num2)
                else:
                    break
                print("The entered number is:", num2)
            except ValueError:
                print("Invalid input. Please enter the next number.")
            else:
                break


        if num2 != str("Exit"):
            num2 = float(num2)
        else:
            break


        match operator:
            case "+":
                num += num2
                print("Answer: [" + str(num) + "]")
            case "-":
                num -= num2
                print("Answer: [" + str(num) + "]")           
            case "*":
                num *= num2
                print("Answer: [" + str(num) + "]")
            case "/":
                num /= num2
                print("Answer: [" + str(num) + "]")
            case _:
                print("error")
        
    
    print("Thank you for using the calculator.")

# -------------------- END OF THE VERSION 2 CALCULATOR --------------------



















# -------------------- VERSION 1 OF THE CALCULATOR ------------------- 

'''
def myCalculator():
    print("Welcome to the CALCULATOR\n")
    
    while True:
        try:
            num = float(input("Enter a number: "))
            print("The entered number is:", num)
        except ValueError:
            print("Invalid input. Please enter a number.")
        else:
            break

    print(num)
    print()
    
    while True:
        try:
            num2 = float(input("Enter the next number: "))
            print("The entered number is:", num2)
        except ValueError:
            print("Invalid input. Please enter a number.")
        else:
            break

    print(num2)



    operator = input("\nChoose the operator you wish to use: ")
    if operator == "+":
        key = True
    elif operator == "-":
        key = True
    elif operator == "*":
        key = True
    elif operator == "/":
        key = True
    else:
        key = False

    while key == False:
        
        operator = input("Invalid input. Please enter an operator(+,-,*,/): ")
        print(operator)

        if operator == "+":
            key = True
        elif operator == "-":
            key = True
        elif operator == "*":
            key = True
        elif operator == "/":
            key = True
        else:
            key = False

    print("The entered operator is: " + operator + "\n")
    


    match operator:
        case "+":
            z = str(num+num2)
            print("The answer is: [" + z + "]")
        case "-":
            z = str(num-num2)
            print("The answer is: [" + z + "]")            
        case "*":
            z= str(num*num2)
            print("The answer is: [" + z + "]")
        case "/":
            z= str(num/num2)
            print("The answer is: [" + z + "]")
        case _:
            print("error")


    print("Thank you for using the calculator.")
'''

# -------------------- END OF THE VERSION 1 CALCULATOR --------------------


    
myCalculator()


