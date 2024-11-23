# PROPER TRENCH COATS
The TrenchCoatsRetail Application is a comprehensive software solution for managing and ordering fashionable trench coats. Designed for both store administrators and customers, the application simulates an online store, simplifying inventory management as well as providing a seamless shopping experience. With features tailored to both roles, it ensures an efficient system for managing the store’s trench coat collection and enabling online purchases.

# Features

## Modes of operation

### Administrator Mode: 
In this mode, store administrators can:
* Manage the Inventory:
  * Add new trench coats: Include details such as size, color, price, quantity, and a link to an online photograph.
  * Delete trench coats: Remove items when they are sold out.
  * Update trench coat details: Modify existing information in the database.
* View All Trench Coats: Display a complete list of trench coats currently in stock, with all relevant details.
### User Mode: 
Allows customers to browse and purchase trench coats.
* Browse Trench Coats:
  * View trench coats of a specific size, one at a time. If no size is specified, all available trench coats are displayed.
  * See details for each trench coat (size, color, price, quantity) along with its photograph.
* Shop for Trench Coats:
  * Add a trench coat to the shopping basket: Automatically updates the total price.
  * Skip to the next trench coat: Continue browsing without adding the current trench coat to the basket. The list cycles back to the beginning once the end is reached.
* View the Shopping Basket:
  * Review all selected trench coats.
  * See the total price of the items in the basket.

# Technologies
The application was built in C++ using the Qt Framework for the graphical user interface. The Observer Pattern ensures real-time updates, reflecting changes made by admins directly in the user mode.
