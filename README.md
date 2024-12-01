# calculate_discount

Create a function named calculate_discount(price, discount_percent) that calculates the final price after applying a discount. The function should take the original price (price) and the discount percentage (discount_percent) as parameters. If the discount is 20% or higher, apply the discount; otherwise, return the original price.


Using the calculate_discount function, prompt the user to enter the original price of an item and the discount percentage. Print the final price after applying the discount, or if no discount was applied, print the original price.


    How It Works:

    Function Logic:
        If the discount percentage is 20% or more, the function calculates the discount using the formula:
        discount=price×(discount percentage100)
        discount=price×(100discount percentage​)
        The final price is then:
        final price=price−discount
        final price=price−discount
        If the discount is less than 20%, the function simply returns the original price.

    User Input:
        The user is prompted to enter the original price and the discount percentage.
        These inputs are converted to float for calculations.

    Output:
        If a discount was applied, the discounted price is shown.
        If no discount is applied, the original price is displayed.

        Example:
        Input:

        Enter the original price of the item: 100
        Enter the discount percentage: 25

        Output:

        The final price after applying the discount is: $75.00

        Input:

        Enter the original price of the item: 100
        Enter the discount percentage: 15

        Output:

        No discount applied. The original price is: $100.00

