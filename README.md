# Hello World Express App

# Overview

This project demonstrates a simple Express.js application that responds with "hello world" to GET requests at the `/hello` endpoint. It serves as a basic introduction to setting up an Express server.

## Setup

1. Clone the Repository
   
   git clone https://github.com/shrutitagade/hello-world-express-app.git
   
   cd hello-world-express-app
 

3. Install Dependencies
   
   npm install
   

5. Create a .env File
   
   Create a `.env` file in the root directory and add the following environment variable:
  
   PORT=8080
   

7. Run the Application
  To start the application, you can use:

  npm start

  Alternatively, for development, you can use:

  npx nodemon src/index.js
 

8. Test the API
   
   Open your browser or use a tool like Postman to test the endpoint:
   
   GET http://localhost:8080/hello
   
   You should receive a response with "hello world".

# Directory Details

- Root Directory (hello-world-express-app/): Contains configuration files, the source directory, and this README file.
- src/index.js: The main entry point of the Express application.

