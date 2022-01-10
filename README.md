# Basic-Programs-Python

print("Select Your Operation")
print("1. ADD")
print("2. SUBTRACT")
print("3. MULTIPLY")
print("4. DIVISION")
print("5: MODULE")


operation = input()

if operation == "1":
    num1 = input("Enter Your First Number:")
    num2 = input("Enter Your Second Number: ")
    print("The Sum Is " + str(int(num1) + int(num2)))

elif operation == "2":
    num1 = input("Enter Your First Number")
    num2 = input("Enter Your Second Number")
    print("The Sum Is " + str(int(num1) - int(num2)))

elif operation == "3":
    num1 = input("Enter Your First Number")
    num2 = input("Enter Your Second Number")
    print("The Sum Is " + str(int(num1) * int(num2)))

elif operation == "4":
    num1 = input("Enter Your First Number")
    num2 = input("Enter Your Second Number")
    print("The Sum Is " + str(int(num1) / int(num2)))

elif operation == "5":
    num1 = input("Enter Your First Number")
    num2 = input("Enter Your Second Number")
    print("The Sum Is " + str(int(num1) % int(num2)))

else:
   print("INVALID SYNTAX PLS TRY ANOTHER OPERATIONS")





