# internship_codsoft
# TASK 2:CALCULATOR
# codsoft #internship #python_programming
print("A Simple Calculator")
num1=float(input("Enter the 1st number: "))
num2=float(input("Enter the 2nd number: "))
print("press 1 for addition \n press 2 for subtraction \n press 3 for multiplication \n press 4 for divison")
choice = int(input("Enter your choice: "))
if choice ==1:
  print("Addition of two number is",num1 + num2)
elif choice ==2: 
  print("Subtraction of two number is",num1 - num2)
elif choice ==3:
  print("Multiplication  of two number is",num1 * num2)
elif choice ==4:
  print("divison of two number is",num1 / num2)
else:
  print("invalid input")
