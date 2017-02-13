# compare_numbers
print("You are going to compare numbers, ok? ")
input("Press RETURN key then, yo  ")
i = 0
j = 0
while i == 0:
    try:
        a = int(input("Enter first number: "))
        i += 1
    except ValueError:
        print("That's not a number, mofo. Go try again ")
first = a
while j == 0:
    try:
        b = int(input("Enter second number: "))
        j += 1
    except ValueError:
        print("You're kidding me, man?! ")
second = b
if first > second:
    print("It's greater... ")
elif first < second:
    print("It's smaller... ")
elif first == second:
    print("Da numbers are the same stuff, man ... ")
