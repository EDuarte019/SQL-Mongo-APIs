#Building NEM

# Step 1
Create a new directory at root.
`mkdir Code-Cardio && cd Code-Cardio`

#step 2 - start you 
Inside the directory `SQL-Mongo-APIs/Code-Cardio`, run `npm init -y` to create a new `package.json` file. Then create a new javascript file for your server, `touch index.js`.

#step 3 - Install Packages
Install the following npm packages:
`npm i express body-parser mongojs mongoose compression morgan helmet http-errors cookie-parser debug`

# Step 4 - Create Express Server
create basic **MVC** structure.
`mkdir models views controllers`
This will create three folders.
**Predict Activity**

#step 5 
`npx express-generator --ejs` then type `y` for yes

#step 6 - Walk through the Express Generator