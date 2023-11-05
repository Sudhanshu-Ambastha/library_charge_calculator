# Python Program to Calculate Library Charges

# Accept the number of days from the user
days = int(input("Enter the number of days: "))

# Initialize the charge variable
charge = 0

# Calculate the charge according to the criteria
if days >= 1 and days <= 5:
    charge = days * 2
elif days >= 6 and days <= 10:
    charge = 5 * 2 + (days - 5) * 3
elif days >= 11 and days <= 15:
    charge = 5 * 2 + 5 * 3 + (days - 10) * 4
elif days > 15:
    charge = 5 * 2 + 5 * 3 + 5 * 4 + (days - 15) * 5
else:
    print("Invalid number of days")

# Display the total charge if it's not zero
if charge > 0:
    print("The total charge is: Rs.", charge)
