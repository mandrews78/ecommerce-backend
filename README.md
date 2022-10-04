# E-commerce-backend
Built a backend for an e-commerce site using Express.js API, using Sequelize to interact with a MySQL database.

## Repository
https://github.com/mandrews78/ecommerce-backend.git

## Demo
https://drive.google.com/file/d/1uWIsjfkrSjzC86WiiyBR6YfN0adMjaIm/view

## User Story
AS A manager at an internet retail company   
I WANT a back end for my e-commerce website that uses the latest technologies   
SO THAT my company can compete with other e-commerce companies  

## Acceptance Criteria
GIVEN a functional Express.js API   
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file    
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands    
THEN a development database is created and is seeded with test data    
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database    
WHEN I open API GET routes in Insomnia Core for categories, products, or tags    
THEN the data for each of these routes is displayed in a formatted JSON    
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core     
THEN I am able to successfully create, update, and delete data in my database 

## Installation
The user should clone the repository from GitHub.  
This application requires Node.js, Express.js, and Sequelize.  
To connect to the database:
- run mysql -u root -p and enter password from .env file.
- Then source the schema.sql.
- To seed the file run: npm run seed.
- To connect to the server run: npm start.

## Technology
- Node.js 
- Express.js API
- Sequelize
- MySQL
- Heroku - https://www.heroku.com/
- Insomnia API - https://insomnia.rest/

## Screenshots
![2022-10-03_23-48-42](https://user-images.githubusercontent.com/70594281/193730846-03624952-8af0-46ff-a464-7dd3affe1a66.png)
![2022-10-03_23-47-36](https://user-images.githubusercontent.com/70594281/193730861-7e31eea8-2d2d-4097-9010-4f1815f431b3.png)
![2022-10-03_23-48-14](https://user-images.githubusercontent.com/70594281/193730869-d07e79c8-2366-473e-adb4-d1ed1523b0f9.png)

## Authors
- [@mandrews78](https://www.github.com/mandrews78)