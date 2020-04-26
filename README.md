# The Marketplace
# LOPEZ, Earth | OLAN, Gabriel

This repository contains the website, The Marketplace. The Marketplace acts as a simple item catalog that can be used by users who wishes to buy items from other users or sell their own items may it be brand new or second hand. As a catalog, the website does not include the Buying and Transaction between users but only provides the necessary information to for contacting them outside the application.

To begin, download the repository as a ZIP file or clone the repository via Github.

# Contents
- delete_data.js => deletes all data that is stored in the database
- add_data.js => adds the dummy values to the database to be used in the application
- index.js => main entry point for the application
- views => folder containing all hbs files to display the pages of the application
- public => folder containing all static files to be used within the pages of the application
- helpers => folder containing js files to be used before performing post to the database.
- routes => folder containing all routes that the server will respond to depending on the method request of the HTTP given a specific path
- controllers => folder containing all actions that the application will execute as callbank functions for client requests
- models => folder containing database models and a script for accessing the database

# Setting up
1. Open command prompt
2. Navigate to the project folder
3. Run npm init and use default for everything
4. Run npm install to download all necessary modules
   * modules to be utilized: express, express-handlebars, handlebars, multer, body-parser, mongoose, mongodb, express-session, bcrypt, connect-mongo, cookie-parser
(to be discussed)
//Before running the application, check if the database is clear by first running node delete_data.js
   Add the dummy data to the database by running node add_data.js
5. You may now start the application by running node index.js or supervisor.js
6. Wait for the prompt to reply "App listening at port 3000" and "Connected to: mongodb://localhost:27017/s11g14"

# Running the Application:
1. Connect to the application by using the browser and entering "localhost:3000" and it will lead you to the Home Page of the Website. All other pages may be accessible through the pages.
2. All other pages may be accessible throught links by the following formats stated below:
   Browse page - input "localhost:3000/browse/(name of Item)"
   Item page - input "localhost:3000/item/(name of Item)" the name of the Item includes entering the spaces and the full name of the item
   Profile page - input "localhost:3000/user/(username of User)" the username needs to completely follow the syntax of the User
   
 Features working:
 - Sign in
  Sample Test Data:
  username: Windoll
  pw: WindollWindoll
  
  success -> profile page
  
 - Registration
  note: images can be uploaded (not viewable)
 
 success -> profile page
 
 - Log out
 
 success -> leads to Home Page
 
 - search (Home Page)
 can search for item names
 ex. Drone, Assorted Toys, Metal Straw Set
 
 - search (Browse, Item, User)
 can search within where the link is (/user/, /item/, /browse/)
 
 - Seller name
 access to seller's profile
 
 - Item card
 access to item page
 
 
