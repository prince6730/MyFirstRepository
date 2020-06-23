# MyFirstRepository

#FaultyCalculator

# taking the first number from user
n1 = int(input("Enter the first Number"))

# taking the second number from user
n2 = int(input("Enter the second Number"))

# verify or confirmed that which operator that you want to performed it
print("choose the opeartor", "+", "-", "*", "/", "%")
n3 = input()

if (n1 == 50 and n2 == 9 and n3 == "+"):
    print(69)
elif (n1 == 90 and n2 == 20 and n3 == "-"):
    print(75)
elif (n1 == 55 and n2 == 9 and n3 == "*"):
    print(400)
elif (n1 == 59 and n2 == 8 and n3 == "/"):
    print(6)

elif(n3=="+"):
    n3=n1+n2
    print(n3)

elif(n3=="-"):
    n3=n1-n2
    print(n3)

elif(n3=="*"):
    n3=n1*n2
    print(n3)

elif(n3=="/"):
    n3=n1/n2
    print(n3)

elif(n3=="%"):
    n3=n1%n2
    print(n3)

else:
    print("Out of range values")
