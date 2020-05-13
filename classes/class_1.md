# Example of a class that might exist in a Restaurant

**Class**

TableOrder

**Attributes**

* server_name (string)
* number_of_customers (integer)
* order_items (hash made up of a string for the item name as a key and the item price as a float value)
* order_closed (boolean - default false)

**Methods**

* change_table (changes the integer value of table_number)
* change_server (changes the name in the server_name variable)
* add_item (appends an item to the order_items hash)
* total_order_price (calculates the total price of the order by summing all the price values in the order_items hash - return value)
* close_order (changes boolean value of order_closed)
