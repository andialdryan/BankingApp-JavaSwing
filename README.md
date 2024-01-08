in this repository I learned to create bank applications using Java Swing from youtube

The following are the features of this application:
 - user registration
 - user login
 - Make a deposit
 - Make a withdrawal
 - Transaction history records
 - Make a transfer

In this application I use the MYSQL Database, I use the MYSQL J Connector driver to connect the application and database. Here is the database schema for this project:

This database table has a one to many relationship to the transaction table, because a transaction can only have one user at a time,
but a user can have multiple transactions.

======= USER TABLE =======
 - PK : id (int)
 - U  : username (varchar)
 - U  : password (varchar)
 - U  : current_balance (decimal)

======= TRANSACTION TABLE =======
 - PK : id (int)
 - FK : user_id (int)
 -    : transaction_type (varchar)
 -    : transaction_amount (decimal)
 -    : transaction_date (date)

Below I have included a link to the YouTube video that I watched to make this project:
https://www.youtube.com/watch?v=phYuQWRaazw

Here is also my LinkedIn link if you want to contact me:
https://www.linkedin.com/in/aldryan-mandala-putra-tune-1950141b2/
