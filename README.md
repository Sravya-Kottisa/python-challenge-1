# Order System
This Python script implements a simple order system for a food truck. Customers can browse the menu, select items, and place orders. The script generates a receipt with the ordered items, quantities, and the total price.
## Features
1. **Menu Display**: The script displays the available menu categories and items, including their prices.
2. **Order Placement**: Customers can select menu items and specify the quantity they want to order.
3. **Order Tracking**: The script stores the customer's order in a list of dictionaries, where each dictionary represents an ordered item.
4. **Receipt Generation**: The script prints a formatted receipt with the ordered items, quantities, and the total price.
## Usage
- Ensure you have Python installed on your system.
- Save the script in a file, e.g., order_system.py.
- Run the script using the following command:
  
     ```python order_system.py ```

- Follow the on-screen instructions to browse the menu, select items, and place your order.
- The script will display the order receipt once you've finished placing your order.
## Code Structure
The script is divided into the following sections:
- **Menu Definition**: The menu dictionary contains the available menu items and their prices.
- **Order List Initialization**: The order list is initialized to store the customer's order.
- **Order Placement Loop**: The script enters a continuous loop to allow the customer to place multiple orders.
- **Menu Selection and Validation**: The customer is prompted to select a menu category, and their input is validated to ensure it's a valid option.
- **Item Selection and Quantity Input**: The customer is prompted to select a menu item and specify the quantity they want to order.
- **Order Tracking**: The selected item, price, and quantity are added to the order list as a dictionary.
- **Order Receipt Generation**: The script loops through the order list and prints a formatted receipt, including the total price of the order.
## Improvements and Future Enhancements
- **Error Handling**: Implement more robust error handling to handle various types of invalid inputs from the customer.
- **Menu Customization**: Allow the store owner to easily modify the menu items and prices by updating the menu dictionary.
- **Order History**: Implement a feature to store and retrieve past orders for the customer.
- **Payment Integration**: Integrate a payment system to allow customers to complete their orders and make payments.
- **User Interface**: Develop a more user-friendly interface, potentially using a GUI library.

## Contributing

If you find any issues or have suggestions for improvements, feel free to reach out at order_support@xyz.com
