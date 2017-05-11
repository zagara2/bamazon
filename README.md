# bamazon

![Before the purchase is made, the item in the mySQL table at position 9 has a stock quantity of 100. In Bash, the user requests to buy 2 of the item with ID 9.](https://github.com/zagara2/bamazon/blob/master/screenshots/db_table_before_purchase.JPG)

![After the purchase of 2 of the item at position 9 is made, the console logs "Order placed!". The stock quantity of the item in the mySQL table at position 9 then goes from 100 to 98. Because the price per item at position 9 was 7 dollars, the console logs "You spent $14!" after the purchase is made.](https://github.com/zagara2/bamazon/blob/master/screenshots/db_table_after_purchase.JPG)

![The user has requested 400 of the item at position 7, which only has a quantity of 25. So, the console logs the message "Insufficient quantity!" and does not change any values in the database.](https://github.com/zagara2/bamazon/blob/master/screenshots/insufficient_quantity_requested.JPG)

![Code entered in mySQL workbench to create the table.](https://github.com/zagara2/bamazon/blob/master/screenshots/mysql_code.JPG)