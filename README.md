**Project Title:** Inventory Management System

**Purpose:** The Inventory Management System is designed to provide a simple yet effective solution for managing a store's inventory. It enables users to add, delete, and view items, ensuring that inventory data is organized, up-to-date, and easily accessible.

**Features:**

**Add Item:** Users can input details for new items, including name, quantity, and price, which are then saved to the inventory.

**Delete Item:** Users can remove items from the inventory by specifying the item's name, allowing for efficient inventory management.

**View Inventory:** The system displays the current list of items, including their names, quantities, and prices, helping users track stock levels.

**Persistent Storage:** Inventory data is stored in a JSON file, ensuring that information is retained across sessions and making it easy to load and save the inventory state.

**Technical Specifications:**

**Programming Language:** Python
Data Format: JSON for storing inventory data

**Key Modules:**
json for handling JSON data
os for file existence checks and management
Implementation:

The project uses two main classes: Item and Inventory.
The Item class encapsulates the properties of individual items and includes a method to convert item data to a dictionary format for easy storage.
The Inventory class manages a collection of Item objects, providing methods for adding, deleting, and viewing items, as well as handling the loading and saving of inventory data from/to a JSON file.
User Interface:

The system operates through a text-based menu that allows users to navigate options for managing the inventory. This makes it straightforward for users to interact with the system without any complex graphical interface.
Benefits:

Streamlines inventory management processes for small businesses.
Reduces the risk of stock discrepancies and ensures accurate record-keeping.
Provides a foundational understanding of object-oriented programming, file handling, and basic user interaction in Python.
Conclusion: The Inventory Management System project demonstrates practical applications of programming concepts in Python, offering users a reliable tool for managing inventory efficiently.
