numbers = []
for i in range(5):
    num = int(input("enter number" + str(i+1) + ":"))
    numbers.append(num)
numbers.sort()
print("sorted list",numbers)