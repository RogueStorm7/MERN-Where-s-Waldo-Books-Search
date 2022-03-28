# Where's Waldo Book Search Engine 

# Table of Contents

* [Summary](#summary)
* [User Story](#)
* [Acceptance-Criteria](#acceptance-criteria)
* [Installation & Database SetUp](#Installation)
* [Tools Used](#tools-used)
* [Screenshot](#Screenshot)
* [Heroku](#Heroku)



## Summary 📖 
I’ll take a fully functioning [Google Books API Search]() engine built with a RESTful API, and refactor it to be a GraphQL API built with Apollo Server. The app was built using the [MERN stack](https://www.geeksforgeeks.org/mern-stack/), with a [React.js](https://reactjs.org/) front end, MongoDB database, and [Node.js](https://nodejs.org/en/)/[Express.js](https://expressjs.com/) server and API. It's already set up to allow users to save book searches to the back end. This data will be stored in a [MongoDB](https://www.mongodb.com/) database.

- When the users loads the search engine. They are taken to the Home Page where. A menu is presented, and they can choose with the options to search the [Google Books API](https://developers.google.com/books) or see books saved in the MongoDB database.

- The Search page has an input component that returns the call from the Google Books API, the information. These __"results"__ are displayed to the user. 

- 

## User Story
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
## Acceptance Criteria
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Sign-up and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Sign-up menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Sign-up
THEN I am presented with three inputs for a username, an email address, and a password, and a sign-up button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the sign-up button
THEN my user account is created and I am logged in to the site
WHEN I enter my account’s email address and password and click on the login button
THEN I the modal closes and I am logged in to the site
WHEN I am logged in to the site
THEN the menu options change to Search for Books, an option to see my saved books, and Logout
WHEN I am logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
WHEN I click on the Save button on a book
THEN that book’s information is saved to my account
WHEN I click on the option to see my saved books
THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
WHEN I click on the Remove button on a book
THEN that book is deleted from my saved books list
WHEN I click on the Logout button
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Sign-up and an input field to search for books and a submit button   
## Installation & Database SetUp
To create your package.json file this app npm init has to be called. You must create at cluster on Mongodb atlas to accurately install the database. 
## Mock-Up
![21-mern-homework-demo-01](https://user-images.githubusercontent.com/89751266/160034953-bbcb30a0-fcb6-4e5c-9d62-8906a6dca200.gif)
-Type `npm start` in the terminal to begin
## Tools Used


* JavaScript
* Node.js
* Express
* React
* Apollo Server
* Graphql
* Mongodb
* Mongoose
* Dotenv
* Heroku
## Screenshot
## Heroku

## License
![badge size](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![badge size](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg)
![License](https://img.shields.io/badge/License-MIT-blue)

## Contact
 - [RogueStorm]("")

© 2022 Mianta McKnight | All rights reserved |