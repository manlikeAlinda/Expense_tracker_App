# Expense_tracker_App
This Is an Expense Tracker App i built with The MERN Stack.
![alt text](https://github.com/manlikeAlinda/Expense_tracker_App/blob/main/HomePage.PNG?raw=true)
Getting Started

This repository aims to assist you in beginning work on a MERN stack application with a solid file structure as a foundation. To get started make a copy of this template repo for your project teams.

Since this project will hold both the client application and the server application there will be node modules in two different places. First run npm install from the root. After this you will run npm run-script install-all from the root. From now on run this command anytime you want to install all modules again. This is a script we have defined in package.json .

This app can be deployed directly to heroku since there is a script defined in package.json which will automatically handle building and deploying the app. For more information on deploying to heroku reference the extra resources at the bottom of this file.

File structure

client - Holds the client application

public - This holds all of our static files

src

assets - This folder holds assets such as images, docs, and fonts

components - This folder holds all of the different components that will make up our views

views - These represent a unique page on the website i.e. Home or About. These are still normal react components.

App.js - This is what renders all of our browser routes and different views

index.js - This is what renders the react app by rendering App.js, should not change

package.json - Defines npm behaviors and packages for the client

server - Holds the server application

config - This holds our configuration files, like mongoDB uri

controllers - These hold all of the callback functions that each route will call

models - This holds all of our data models

routes - This holds all of our HTTP to URL path associations for each unique url

tests - This holds all of our server tests that we have defined

server.js - Defines npm behaviors and packages for the client

package.json - Defines npm behaviors like the scripts defined in the next section of the README

.gitignore - Tells git which files to ignore

README - This file!

Available Scripts

In the project directory, you can run:

npm run start
Runs both the client app and the server app in development mode.

Open http://localhost:3000 to view the client in the browser.

npm run-script server
Runs just the server app in development mode.
Open http://localhost:5000 to view the client in the browser.

npm run-script server
Runs just the server in development mode.

npm run build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

See the section about deployment for more information.
