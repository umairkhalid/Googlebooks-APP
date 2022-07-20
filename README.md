# Googlebooks APP

![full-stack](https://img.shields.io/badge/MERN-1?label=full-stack&style=for-the-badge&labelColor=orange&color=black)

![MongoDB](https://img.shields.io/badge/-MongoDB-darkgreen) ![Express](https://img.shields.io/badge/-Express-orange) ![React](https://img.shields.io/badge/-React-yellow) ![NodeJS](https://img.shields.io/badge/-NodeJS-darkred)

![Apollo-Client](https://img.shields.io/badge/3.6.9-0?label=Apollo-Client&style=flat-square&labelColor=yellow&color=black) ![GraphQL](https://img.shields.io/badge/16.5.0-0?label=GraphQL&style=flat-square&labelColor=darkred&color=black) ![jsonwebtoken](https://img.shields.io/badge/8.5.1-0?label=jsonwebtoken&style=flat-square&labelColor=darkgreen&color=black) ![mongoose](https://img.shields.io/badge/5.9.10-0?label=mongoose&style=flat-square&labelColor=darkblue&color=black)

## Description

This project is emblematic of the fact that most modern websites are driven by two things: data and user demands. This shouldn't come as a surprise, as the ability to personalize user data is the cornerstone of real-world web development today. And as user demands evolve, applications need to be more performant.

It takes the starter code with a fully functioning Google Books API search engine built with a RESTful API, and refactors it to be a GraphQL API built with Apollo Server. The app was initially built using the MERN stack with a React front end, MongoDB database, and Node.js/Express.js server and API. It's already set up to allow users to save book searches to the back end. 

Following refactoring has been done in order to build the GraphQL API with Apollo Server:

1. Apollo Server has been setup to use GraphQL queries and mutations to fetch and modify data, replacing the previous RESTful API.

2. Existing authentication middleware has been modified, so that it works in the context of a GraphQL API.

3. Create an Apollo Provider so that requests can communicate with an Apollo Server.

4. Application has been deployed to Heroku at [Googlebooks APP](https://books-google-app.herokuapp.com/).


## User Story

```md
AS AN avid reader
I WANT to search for new books to read
SO THAT I can keep a list of books to purchase
```


## Acceptance Criteria

```md
GIVEN a book search engine
WHEN I load the search engine
THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
WHEN I click on the Search for Books menu option
THEN I am presented with an input field to search for books and a submit button
WHEN I am not logged in and enter a search term in the input field and click the submit button
THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
WHEN I click on the Login/Signup menu option
THEN a modal appears on the screen with a toggle between the option to log in or sign up
WHEN the toggle is set to Signup
THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
WHEN the toggle is set to Login
THEN I am presented with two inputs for an email address and a password and login button
WHEN I enter a valid email address and create a password and click on the signup button
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
THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button  
```


## Mock-Up

Let's start by revisiting the web application's appearance and functionality.

As you can see in the following animation, a user can login with their credentials and type a search term (in this case, "star wars") in a search box and the results appear

The user can save books by clicking "Save This Book!" under each search result, as shown in the following animation

Then user can view their saved books on a separate page, as shown in the following animation:

![Books page shows the books that the user has saved.](./client/assets/app_demo.gif)

## Table of Contents

- [Technologies](#technologies)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## [Technologies](#table-of-contents)
---

- `M`ongoDB (Mongoose)
- `E`xpress
- `R`eact
- `N`odeJS
- GraphQL
- Apollo Server
- Apollo Client 3.0
- Bcrypt
- Json Webtokens
- Concurrently
- JavaScript
- React-Bootstrap
- HTML
- Deployed on GitHub Pages

## [Usage](#table-of-contents)
---

- The app is deployed at: https://books-google-app.herokuapp.com/
- The repo is at: https:https://github.com/umairkhalid/Googlebooks-APP



```sh
git clone https://github.com/umairkhalid/Googlebooks-APP.git

cd Googlebooks-APP
```

### Install dependencies

```sh
npm install
```

### Start the app

```sh
npm run develop
```
## [License](#table-of-contents)

The application is covered under the following license: [MIT](https://choosealicense.com/licenses/mit/)

## [Questions](#table-of-contents)

If you have any question about the repo, open an issue or complete the form at [Contact](https://umairkhalid.github.io/react-portfolio/#contact).

You can find more of my work at [GitHub](https://github.com/umairkhalid).

---
© 2022 Umair Khalid. Confidential and Proprietary. All Rights Reserved.
