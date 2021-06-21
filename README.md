# ORM_E-commerceBackEnd

## Description
  A back-end application for an e-commerce site. 

  [insert GIF]

  See the full demonstation here: 


  ## Table of Contents

  * [Installation](#installation)
  * [Usage](#usage)
  * [User Story](#userstory)
  * [License](#license)
  * [Questions](#questions)
  
  ## Installation   
  Clone the repo:
     ``` 
    git clone git@github.com:thuylienvo/ORM_E-commerceBackEnd.git   
    ```
          
  Install the following dependencies and packages:    
  * Node.js   
  * MYSQL2    
  * Express.js   
  * Sequelize   
  * dotenv    

  ## Usage 
  Installation will require installing the dependencies listed above. From the root directory, access MqSQL shell and run the following:    
  ```
  source db/schema.sql
  ```   
  Confirm the DB has been successfully created by running: 
  ``` 
  SHOW databases 
  ```
  Then select the DB with: 
  ```
  USE ecommerce_db
  ```
  Quit MqSQL shell once completed. In your terminal, run the following commands:   
  ```
  npm run seed
  ```
  Intiate the application with:
  ```
  node server.js
  ```

  Make sure you have Insomnia Core installed. Utilize the app to run the different routes:   
  * PUT   
  * POST   
  * GET   
  * DELETE   


  ## User Story
  AS A manager at an internet retail company   
  I WANT a back end for my e-commerce website that uses the latest technologies   
  SO THAT my company can compete with other e-commerce companies   

  ### Acceptance Criteria
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
  ## License  

  This repo is licensed under the MIT License. (https://opensource.org/licenses/MIT) 

  ## Questions
  For any questions, connect with me at [mimzy414@gmail.com](mailto:mimzy414@gmail.com). 
  
  GitHub: [thuylienvo](https://github.com/thuylienvo) 

