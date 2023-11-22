# E-commerce Back End 

## Description

The motivation behind creating this project was to get hands on experience with Mysql2, and sequalizer,  
with an application that is trendy at the moment; being e-commerce.  
The problem the project solves for the user is one of organization and ease of use.
I learned more about route handling, squealizer, one to one, and one to many relationships. 


```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation

 1. log into mysql
 2. Navigate to 'db' directory
 * source schema.sql;
 *  quit;
 3. Navitgate to the root directory
 4. Install dependencies
 * npm i
 5. Populate database
 * npm run seed
 6. Have fun Organizing and updating the Database

 ## Usage

 ![“GET tags,” “GET Categories,” and “GET All Products. “GET tag by id,” “GET Category by ID,” and “GET One Product.” “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Develop/assets/commerceGIF.gif)

# Credits

[Sequealize.org](https://sequelize.org/api/v7/functions/_sequelize_core.decorators_legacy.autoincrement "AutoIncrememnt").

## License
[MIT LICENSE](https://choosealicense.com/licenses/mit/ "LICENSE")