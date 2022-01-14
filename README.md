# Homework-eCommerce-Back-End
Express.js API routing using Sequelize to interact with a MySQL database to create, update and delete items in an eCommerce database.

We were given the following acceptance criteria:
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
- **What was your motivation?**
```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
- **Why did you build this project?**
I built this project to practice creating routes that manipulate a database using the Object Relational Mapping with Sequelize. Using the example of an eCommerce site, I wanted to gain an understanding of the fundamental architecture of these prevelent platforms benefit my full-stack web development skills.

- **What problem does it solve?**
This allows a business to be able to manage product categories, tags and the products themselves.

- **What did you learn?**
I learned how to use Sequelize as an ORM to create, read, update, and delete data in a database when hitting the proper routes with GET, POST, PUT and DELETE routes.

- **What challenges did you encounter?**
Writing the routes and including the proper object data.
  
 ## Installation 
 Make sure to include mySQL credentials in an .env file and do an "npm install" before running this application. Run "npm run start" to start the server to be able to hit the routes using localhost3001.
 
 ## Usage
 Link to watch application running: https://watch.screencastify.com/v/63o8ukjemDCjqUVytQGY


## Credits  
Assignment from The Coding Boot Camp at UC San Diego Extension in Partnership With Trilogy Education Services, LLC, Full Stack Part-Time Flex, September 2021 Cohort


