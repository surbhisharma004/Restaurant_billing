
## RESTAURANT BILLING
Struct Definitions:

struct items: Represents information about each item in the order, including the item name, price, and quantity.

struct orders: Represents an order, containing customer details, date, the number of items, and an array of items.

Functions:

generateBillHeader: Generates the header of the bill, including the restaurant name, date, invoice recipient, and a table header.

generateBillBody: Generates the body of the bill for each item, including the item name, quantity, and total price.

generateBillFooter: Generates the footer of the bill, including sub-total, discount, net total, CGST, SGST, grand total, and a thank-you message.

Main Functionality:

Generate Invoice:

Takes customer details, date, and the number of items in the order.
For each item, it prompts the user to enter item details (name, quantity, and price).
Calculates the total amount and generates a bill with header, body, and footer.
Optionally, the user can save the invoice to a file.

Show All Invoices:

Reads and displays all previously saved invoices from a file.

Search Invoice:

Takes a customer name as input and searches for the corresponding invoice.
Displays the invoice details if found; otherwise, shows a message indicating that the invoice does not exist.

Exit:

Exits the program.

File Handling:
The program uses file handling to save and read invoices to/from a file named "RestaurantBill.dat."

User Interface:
Displays a menu with options to generate an invoice, view all invoices, search for an invoice, or exit the program.
After each operation, the user is prompted if they want to perform another operation.
