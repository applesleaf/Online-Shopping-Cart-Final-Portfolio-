This program is designed to help you manage a shopping cart using Python. It includes two main classes: `ItemToPurchase` and `ShoppingCart`, and a menu system to interact with these classes.

### ItemToPurchase Class
The `ItemToPurchase` class represents an item you want to buy. It has attributes like the item name, price, quantity, and description. When you create an instance of this class, these attributes are initially set to default values. The class also includes methods to print the cost and description of the item.

### ShoppingCart Class
The `ShoppingCart` class represents a shopping cart for a customer. It includes the customer's name, the current date, and a list of items in the cart. The class has several methods to manage the cart:

- **add_item**: Adds an item to the cart.
- **remove_item**: Removes an item from the cart by name.
- **modify_item**: Modifies the details of an item already in the cart.
- **get_num_items_in_cart**: Returns the total quantity of items in the cart.
- **get_cost_of_cart**: Returns the total cost of the items in the cart.
- **print_total**: Prints the total cost and details of all items in the cart.
- **print_descriptions**: Prints the descriptions of all items in the cart.

### Menu System
The `print_menu` function presents a menu to the user, allowing them to add items, remove items, change item quantities, print item descriptions, or print the shopping cart's total cost. The user interacts with the menu by entering different commands.

### Main Function
The `main` function is the starting point of the program. It prompts the user for the customer's name and today's date, creates a `ShoppingCart` object, and then displays the menu.

### Example Usage
When you run the program, you first enter the customer's name and today's date. The program then shows a menu with options to add items, remove items, change item quantities, print item descriptions, and print the shopping cart's total. You can select any of these options by entering the corresponding letter.

Overall, this program helps you manage a shopping cart by adding, removing, and modifying items, and it calculates the total cost of the items in the cart.
