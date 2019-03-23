# MERN_BASE
#### A base for with MongoDB/Express/React/NodeJS.

### Installing
npm i will install all requirements on all levels.
```
$ npm i
```

### Running
Make sure MongoDB is running. Then run npm start.
```
$ npm start
```

#### This will run:
* Server-side will create a database called MERN-setup.
* Client-side (React) will make one post-request to create a user with an email.
* Then fetch that user and display it.

### What's in it?
#### Server:
* Express (backend framework)
* MongoDB/Mongoose (database + handler)
* Cors (needed for client-side to call server-side)
* Morgan (logger - NN)

#### Client:
* React (frontend framwork
* Axios (easier requests - NN)
* Node-sass (to be able to import sass into react - NN)
* Http-proxy-middleware (makes it possible to make requests with /api/request - NN)

#### Others:
* Postinstall (to call something after the npm install is complete - NN)
* Concurrently (run more than one script at one time - NN)

#### NN === Not needed
