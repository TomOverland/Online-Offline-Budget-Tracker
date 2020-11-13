# Online-Offline-Budget-Tracker
Progressive web application that allows users to add expenses to a budget tracker both online and offline.  

[Deployed on Heroku](https://secret-tor-92519.herokuapp.com/).

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Technology Used](#technology-used)
- [Built With](#built-with)
- [License](#license)
- [Demonstration](#demonstration)
- [Questions](#questions)


## Description:

This application allows a user to add expenses and deposits to a budget tracker with or without an internet connection.  When entering transactions offline, they will update the total when the user reconnects to the internet.  This application demonstrates a simple full stack development CRUD application with front end implemented with HTML and CSS.  The backend is implemented with Node.js and Express. The database was constructed with Mongoose, MongoDB, and IndexedDB, and implemented to Heroku with MongoDB Atlas.

![Screenshot of Application](screenshot-of-application)


## Installation:

#### Step 1 - Make sure you have a code editor, MySQL, Node.js and Node Package Manager installed

The code editor I used was Visual Studio Code. It can be found [here](https://code.visualstudio.com/download).  
Node.js and NPM download can be found [here](https://nodejs.org/en/).  
MongoDB can be found [here](https://www.mongodb.com/try/download/community).

#### Step 2 - Clone my repository

In your command terminal, type the following to clone this repository: "git clone https://github.com/TomOverland/Online-Offline-Budget-Tracker.git"

#### Step 3 - Move to the correct directory

Type the following in your command line: "cd Online-Offline-Budget-Tracker"

#### Step 4 - Install NPM dependencies

By typing "npm install" you will download all of the dependencies required for this application.

#### Step 5 - Start the application on your local server

Type the following in your command line: "node server.js" and then go to the url "localhost:3000" in your internet browser.  

## Technology used
* Node.js
* Heroku-cli NPM Package
* Express NPM Package
* Express-Handlebars NPM Package
* Charts.js NPM Package
* MongoDB
* Mongoose NPM Package
* MongoDB Atlas
* HTML 5
* CSS 3
* JavaScript
* Path NPM Package
* Morgan NPM Package

## Built With
* VS Code - https://code.visualstudio.com/
* MongoDB - https://www.mongodb.com/

## License:

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

For more information about the license, click the link below:

- [License](https://opensource.org/licenses/)

## Contributing:

Everyone is welcome to contribute. Create a pull request with your changes and I will review it. Currently, I only have instructions written in English. Translations to other languages would be appreciated!

## Tests:

This application was not developed with any tests.

## Demonstration

If you inspect the page using Google Dev Tools, you can simulate an offline experiance from the Network tab.

(image of Network tab)

Once you've gone "offline" you can add or subtract costs to the budget tracker, and observe those items pending upload if you check the IndexedDB database located in the Application tab.  You will likely have to "reload" the IndexedDB information to see the pending entry.

(image of application tab)

- [YouTube](youtube-link)

## Questions:

For more information about the application, please reach out to me via my [GitHub Profile](https://github.com/TomOverland).

For any other questions, please send me an email at: thomas.c.overland@gmail.com.

