# J.A.T.E Text Editor

## User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

## Acceptance Criteria
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application


## Description
  Just Another Text Editor (J.A.T.E) is a progressive web application that runs in the browser and can also function offline. It uses 


## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [Features](#features)
  - [License](#license)


  ## Installation
  Clone the respository from the repo in GitHub to your local machine. Make sure you have Node.js and installed on your computer. Run `npm install` to install dependencies and `npm run start: dev` to start the application.


  ## Usage
  The application has been deployed to Heroku. The URl of the deployed application is _____________.

  

  ![social network api gif](./images/social-network-api-walkthrough.gif)

  ![social network api routes](./images/social-network-api-routes.png)


 
 
  

## Features
* NodeJS
* Express
* Mini-CSS-Extract Plugin
* IndexedDB
* Webpack
* Workbox
* Babel



## License
The project is licensed under MIT. For more information, please refer to the LICENSE in the repo.
  