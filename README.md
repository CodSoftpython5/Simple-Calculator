# Simple-Calculator
#A simple calculator with basic arithmetic operations.Prompt user to input two numbers and an operation and display the result.
num_1 = int(input("Enter first number: "))
num_2 = int(input("Enter second number: "))

print("Select the Operation from following: \n 1.Addition \n 2.Subtraction \n 3.Multiplication \n 4.Division")

operation = int(input("Operation to be selected : " ))

if operation==1:
	print(num_1, "+", num_2, "=",(num_1+num_2))
elif operation==2:
	print(num_1, "-", num_2, "=",(num_1-num_2))
elif operation==3:
	print(num_1, "*", num_2, "=",(num_1*num_2))
elif operation==4:
	print(num_1, "/", num_2, "=",(num_1/num_2))
else:
	print("Invalid input")
