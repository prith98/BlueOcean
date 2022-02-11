# "Thumbs Up" - The Next Gen RideShare App

## Background

*Thumbs Up* is a full-stack rideshare application created during my tenure at Hack Reactor.

- Mitchell Gardner - *Product Manager & Software Engineer*
- Prith Jaganathan - *Architecture Owner & Software Engineer*
- Neil Mosster - *UI Owner & Software Engineer*
- Matt Dziedzic - *Software Engineer*
- Sterling Muller - *Software Engineer*
- Ezra Pullido - *Software Engineer*


These six developers were given roughtly 10 days to build out a fullstack web application from scratch according to a rough concept from a client.

---

## Primary Technologies

This application was built using the following primary technologies

- **ReactJS**
    - Frontend javascript framework used to build the user interface.
- **React Router**
    - Complementary library to ReactJS responsible for conditionally rendering the app's views based on the current URL.
- **CSS/Bootstrap**
    - Utilized popular Bootstrap components such as Buttons, Forms, and Cards to have consistent styling across the app
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

---

## My Features

- Users can securely log in with username/password combination. Invalid combination of username/password will in an error alert. 
- New Users can create an account by pressing on the appropriate button. If users try to use a username already in the database, they will receive an error alert. Upon successfuly creating an account,  users are redirected to the login page
- Upon successfully logging in, users are taken to a landing page where they can choose to use the app as a rider or driver. Selecting on either the rider/driver image will take the user to the respective portal for riders/drivers. 

