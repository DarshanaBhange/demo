for i in range(5):
    num = int(input("Enter number " + str(i+1) + ": "))
    numbers.append(num)

# Sort the list
numbers.sort()

# Print the sorted list
print("Sorted list:", numbers)