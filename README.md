# "Thumbs Up" - The Next Gen RideShare App

## Background

*Thumbs Up* is a full-stack application created for the Hack Reactor software engineering immersive program.

- Mitchell Gardner - *Product Manager & Software Engineer*
- Prith Jaganathan - *Architecture Owner & Software Engineer*
- Neil Mosster - *UI Owner & Software Engineer*
- Matt Dziedzic - *Software Engineer*
- Sterling Muller - *Software Engineer*
- Ezra Pullido - *Software Engineer*


These six developers were given roughly 1.5 weeks to build out a fullstack web application from scratch according to a rough concept from a client.

---


## Primary Technologies

This project's client app was built using the following primary technologies

- **ReactJS**
    - Frontend javascript framework used to build the user interface.
- **React Router**
    - Complementary library to ReactJS responsible for conditionally rendering the app's views based on the current URL.
- **PostgreSQL**
    - Went with SQL DB over a NoSQL DB (Mongo) due to the fact that user data and ride data were intertwined enough 
- **Babel**
    - Transpilation package used to convert ReactJS-specific syntax into browser-consumable JavaScript.
- **Passport JS**
    - Authentication Middleware that stores successful login sessions server side
- **Webpack**
    - Bundling package used to bundle javascript modules and component-focused stylesheets into ```.js``` and ```.css``` bundles for browser comsumption.
- **Jest + React-Testing-Library**
    - Testing framework and library used for unit tests, integration tests, and end-to-end tests.

## Features

- My job applications: Table where a user can add, edit, sort, and delete their job applications. Users can add the URL to the job description, the job title, company, date added, and status.
- Career advice: Users can see cards displaying relevant career advice articles from The Muse. Users can click on a card to see the full article.
- Authentication: A user can create a new account, login, and logout of the app. While logged in, they will see their own job applications.

