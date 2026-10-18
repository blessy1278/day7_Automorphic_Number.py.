# day7_Automorphic_Number.py.

num = int(input("Enter a number: "))

digits = len(str(num))
square = num * num
last = square % (10 ** digits)

if last == num:
    print("Automorphic number")
else:
    print("Not an Automorphic number")
