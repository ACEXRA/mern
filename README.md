# MernStack application

This repo has a simple mern stack application(mongoDB,ExpressJs,ReactJs,NodeJs) with login authentication.

## Dependencies

### Backend

- ExpressJs - a framework of nodeJs helpful in creating api services.
- Mongooose - package to connect to mongoDb.
- dot-env - for .env file configuration.
- cookie-parser - to parse the token and cookie management in browser.
- bycrypt - to hash the password.
- jsonwebtoken - for token creation.

### Frontend

- Reactjs - Frontend framework
- React Router - routing for webpage
- Vite - for quickstart of react template
- Bootstrap - CSS framework
- Redux - state management

## Installation

Open the project in VScode
For all backend dependecies installation

```sh
npm i
```

For frontend dependencies installation

```sh
cd frontend
npm i
cd ..
```

Make Sure to create an real .env file with necessary value as shown

```sh
NODE_ENV=production
PORT=5000 #PROVIDE PORT VALUE ON WHICH IT NEED TO RUN
MONGO_URI=YOUR_URI
JWT_SECRET=WITH A VALUE(EXAMPLE:SANJI123)
```

Finally "npm run dev"
The webpage with run on [localhost:3000](http://localhost:3000/)
And api will run in port 5000.
