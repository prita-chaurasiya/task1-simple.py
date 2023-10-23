#1.ADD
#2.SUBTRACT
#3.MULTIPLY
#4.DIVIDE
    
print("Select an operation to perform: ")
print("1. ADD")
print("2. SUBTRACT")
print("3. MULIPLY")
print("4. DIVIDE")

operation = input()

if operation == "1":
    num1 = input("enter first number: ")
    num2 = input("enter scond number: ")
    print("the sum is  " + num1 + num2)
elif operation == 2:
    num1 = input("enter first number: ")
    num2 = input("enter scond number: ")
    print("the sum is  " + num - num2)
elif operation == 3:
    num1 = input("enter first number: ")
    num2 = input("enter scond number: ")
    print("the sum is  " + num * num2)
elif operation == 4: 
    num1 = input("enter first number: ")
    num2 = input("enter scond number: ")
    print("the sum is  " + num / num2)
else:
    print("Invalid entry")

if operation == "1":
    num1 = input("enter first number: ")
    num2 = input("enter second number: ")
    print("the sum is " + str(int(num1) + int(num2)))
