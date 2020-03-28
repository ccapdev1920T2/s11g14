# The Marketplace
# LOPEZ, Earth | OLAN, Gabriel

This repository contains the website, The Marketplace. The Marketplace acts as a simple item catalog that can be used by users who wishes to buy items from other users or sell their own items may it be brand new or second hand. As a catalog, the website does not include the Buying and Transaction between users but only provides the necessary information to for contacting them outside the application.

Setting up the Website:
1. Run npm init and use default for everything
2. Run npm install to download all necessary modules
3. Before running the application, add the necessary data to the database first by running node add_data.js
4. You may now start the application by running node index.js or supervisor.js

In Running the Application:
1. Connect to the application by using the browser and entering "localhost:9090" and it will lead you to the Home Page of the Website.
2. All other pages may be accessible throught links by the following formats stated below:
   Browse page - input "localhost:9090/browse"
   Item page - input "localhost:9090/(name of Item)" the name of the Item includes entering the spaces and the full name of the item
   Profile page - input "localhost:9090/(username of User)" the username needs to completely follow the syntax of the User
