# Adonis 5 emoji database in MYSQL
## Common errors:
* Emoji into database 
* Incorrect string value: '\x... 
* How to store Emoji Character in MySQL Database

## How to solve?
**First**, convert your database, tables and column

Article suggestion for this: https://mathiasbynens.be/notes/mysql-utf8mb4#character-sets

**Second**, add charset in your connection

Suggestion on how to do it: https://github.com/adonisjs/core/issues/509

*If you still have a problem with this, open a issue please*
So that we can get more information and help others
