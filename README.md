Portfolio Website
This is a portfolio website where users can create, view, update and delete their portfolios. The website is hosted in Netlify and built using the MERN stack.

Table of Contents
Technologies
Features
Setup
Usage

Technologies
The following technologies were used in building this website:

MongoDB: A NoSQL document database used to store user data.
Express: A Node.js web application framework used for building the backend APIs.
React: A JavaScript library used for building the frontend UI components.
Node.js: A JavaScript runtime environment used for running the backend server.
Netlify: A cloud hosting platform used to deploy the website.
Features
The following features are available in the website:

User authentication: Users can create an account and login to access their portfolios.
Portfolio creation: Users can create a portfolio by providing their name, description, and uploading an image.
Portfolio editing: Users can edit their portfolios by updating the name, description, and image.
Portfolio deletion: Users can delete their portfolios from the website.
Portfolio view: Users can view their portfolios and portfolios of other users.
Setup
To set up the website locally, follow these steps:

Clone this repository to your local machine.
Install the dependencies by running npm install in the root directory.
Create a .env file in the root directory and set the following environment variables:
MONGODB_URI: the MongoDB connection string
JWT_SECRET: a secret key used to sign and verify JSON Web Tokens
Start the server by running npm start in the backend directory.
Start the frontend by running npm start in the frontend directory.
Usage
To use the website, follow these steps:

Go to the website URL.
Create an account by providing your name, email, and password.
Login using your email and password.
Create a portfolio by providing your name, description, and uploading an image.
Edit or delete your portfolio as needed.
View your portfolio and portfolios of other users.
