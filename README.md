#Node.JS REST API with Authentication built with Node.js, Express, MongoDB and JSON Web token.


##About this Project

This project is a CRUD REST API that allows users to create, read, update and delete resources from an application. This API can be connected to a front end framework such as react, angular or vue to build a full stack project that has CRUD functionality.


##Why I built this project

I decided to build a complete backend application to demonstrate my ability to work on server side projects. My previous projects have been more client-side and I wanted to stretch my technical skills by working on a server side project. This project was a great opportunity to see Javascript in action on the server side and understand how REST APIs can be secured properly and easily. The original intention of the project was to build a full stack application but I decided to leave it as a REST API so other developers, who might need an authenticated REST API for their project, can use this repository.


##Who can use this project?

This project can be used in full stack projects/applications with CRUD (Create, Read, Update and Delete) functionalities. As most of the heavy lifting is done, you only need to focus on working on the front end part of your application, thus cutting down on development time. Depending on your project needs, you may need to make some adjustments in some parts of the codebase. For example, changing the name of the routes, controllers and schemas to match your project.



##How to use this project

###To use this project, you will need to have the following
- latest version of Node.js  
- Postman installed on your machine to test your APIs and make sure it is working properly before connecting to the frontend  
- MongoDB account.

###To begin with this project: 
1. Clone this repository by running the following command in your terminal `git clone <url>`
2. Run the following command `npm i mongoose express cors colors dotenv nodemon jsonwebtoken bcryptjs`. These are the dependencies that are needed to run this applicaton on the server side.
3. Once the dependcies are installed, create .env and .gitignore files. 
4. Your .gitignore file should have the following lines of code 
5. Your .env should have the following lines of code.
6. Connect your application to your mongoDB database 
7. To connect your MongoDB database your application: 
- create a cluster (go for the shared option which is free and use AWS as the cloud provider)
- create a username and password for your cluster
- connect to your application with the URI 
- add the URI to your .env file

**see below for a link to a more detailed tutorial to guide on how to connect your server and database in MongoDB**

With your database now connected to your application, run `npm start` to start the sever. If everything works fine, you should see a connection message for the server with a port number and a connection message to the database.

Your REST API is now ready to use.
Goodluck and happy coding!
