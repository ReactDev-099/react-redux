## Full Stack Web Application( MongoDB, NodeJs, Express, React, Redux )
<p align="center">
  <img src="https://img.shields.io/badge/Mongoose-5.1.1-blue.svg?colorB=449a45">
  <img src="https://img.shields.io/badge/React-16.3.2-blue.svg">
  <img src="https://img.shields.io/badge/Redux-4.0.0-blue.svg?colorB=764abc">
  <img src="https://img.shields.io/badge/Nodejs-9.11.1-blue.svg?colorB=90c53f">
  <img src="https://img.shields.io/badge/Express-4.16.  3-blue.svg?colorB=47535e">
  <br/>
</p>

#### Backend features

The Mongo database was hosted at MLab for convenience. Gravatar has been implemented for profile photo, if the user's email has a wordpress avatar it is automatically saved to the bank. Sensitive routes were protected through JWT in conjunction with passport.


#### Using
- Nodejs
  * Express, Nodemon, Passport, Jwt, Bcrypt
- MongoDB
  * Mongoose

#### Frontend features
React was used in conjunction with Redux and React-router to build the SPA.
Protected routes redirect to home and are only accessible through auth.
Localstorage was used to persist user state when reloading pages.

#### Using
- React
  * Redux, asyncRoutes
- Axios
- Local storage native
- MaterialUI components

#### Requerimentos

- Node.js
- NPM

### Installing the packages

Run the command below to install the dependencies:
``` bash
npm install
```

### Starting the server

Run the command below to start Nodejs and connect to the MongoDB database:
``` bash
npm run server
```

Wait execution and the API will be running on Url  `http://localhost:8001/api/`

Os endpoints disponíveis são:
- Post - Login
- Post - Register
- Put  - Update Profile
- Del  - Delete Account
- Get  - List Users

Leave the server running on one terminal, open another, and proceed to the next step:
### Starting SPA React

For that just run the command below, and you're done! : D
``` bash
npm start
```

The application will launch automatically in the browser at Url http://localhost:3000

<br/>
