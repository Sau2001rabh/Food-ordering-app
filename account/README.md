# Food Ordering System

How To Install -
---------

1. Create Database food.
2. Run food.sql script provided in sql folder.
3. Go to login.php and try out our application. Sample user credentials can be found in the users & wallet_details table.

Note -
---------
1. This is not ready for PRODUCTION.
2. The username and password of sample users are stored in the table `users`.
3. Only Customers with "Verified" status can place orders using the "Cash on Delivery" option.
4. By default a new customer gets 2000 coins in Wallet on signing up, and a fake Credit card number & CVV number are generated and stored in SQL Table "wallet_details" with the corresponding new customer's ID.
5. Use that Card Number & CVV while placing an order, else order won't be successful or use "Cash on delivery" option.
6. What's lacking? Dynamic payment(real payment system) and error reporting are lacking in this project. And also one might wish to show the corresponding food item's photo and all that stuff.
