"""
Description: This program calculates the total sales for each day of the week based on the unit prices of pies and the quantities sold per day.

Functions:
- calculate_daily_sales(price, pie): Calculate total sales for each day.
Inputs:
- price: List of pie prices (one-dimensional).
- pie: 2D list of pies sold per day (two-dimensional).
Output:

Author: Cherry

"""
# Define a function to calculate daily sales
def calculate_daily_sales(price, pie):
    """
    Calculate total sales for each day.
    :param price: List of pie prices (one-dimensional).
    :param pie: 2D list of pies sold per day (two-dimensional).
    :return: List of total sales for each day.
    """
    daily_totals = []  # Initialize an empty list to store daily sales totals

    # Loop through each column (day) in the 2D list 'pie'
    for day in range(len(pie[0])):  # len(pie[0]) gives the number of days
        daily_total = 0  # Initialize daily total to 0
        for pie_type in range(len(price)):  # Loop through each pie type
            # Calculate sales for the current pie type and add to daily total
            daily_total += price[pie_type] * pie[pie_type][day]
        daily_totals.append(daily_total)  # Append the daily total to the list

    return daily_totals  # Return the list of daily totals

# Define matrix 'price' as a one-dimensional list (unit prices for pies)
price = [3, 4, 2]  # Prices for Apple, Cherry, and Peach pies

# Define matrix 'pie' as a two-dimensional list (quantities sold per day)
pie = [
    [13, 9, 7, 15],  # 1st row: Quantities of Apple pies sold Mon-Thu
    [8, 7, 4, 6],    # 2nd row: Quantities of Cherry pies sold Mon-Thu
    [6, 4, 0, 3]     # 3rd row: Quantities of Peach pies sold Mon-Thu
]

# Call the function to calculate daily sales
daily_sales = calculate_daily_sales(price, pie)

# Print the daily sales totals in a readable format
print("Mon  Tue  Wed  Thu")  # Print the header for days
for total in daily_sales:  # Loop through each daily total
    print(f"${total}", end="  ")  # Print the total sales for each day
