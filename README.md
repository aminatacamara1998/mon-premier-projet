income = int(input("Enter your monthly income in dollars: ")
rent = int(input("Enter your rent in dollars: ")
food = int(input("Enter your food expenses: ")
transport = int(input("Enter your transport expenses: ")
other = int(input("Enter your other expenses: ")

total_expenses = rent + food + transport + other
balance = income - total_expenses

print("\n------ BUDGET SUMMARY ------")
print("Income:", income)
print("Total expenses:", total_expenses)
print("Remaining balance:", balance)

if balance > 0:
    print("Good management: you still have money left.")
elif balance == 0:
    print("Warning: your budget is zero.")
else:
    print("Alert: you are in deficit.")
