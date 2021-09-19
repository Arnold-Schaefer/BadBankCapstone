# BadBankCapstone

Full-Stack Bad Bank Capstone Project for the MIT xPRO Development Bootcamp

### Description/Motivation

This bad bank project uses a 3 tier system including a react front end hosted on an HTTP server using node and express and then a back end of mongoDB and docker. It is the first full assignment that incorporates the entire stack and runs off of an independent server.

### Installation Guidelines

Download all of the files to your PC and put them in the folder. 

Go to Firebase.com and create a project. Once the project is created:
  1. Go to your project settings
  2. Under 'General', add a web app
  3. Find the SDK setup and configuration section for your new app
  4. Copy the code for the firebase config
  5. Add this code to the index.html file in the public folder in the project and save the file

After adding your firebase credentials, open a terminal window and run the following command (make sure you have docker installed an running):
  1. *'docker-compose up'*

Then do the following:
  1. Open another terminal window in the root folder of the project and run *'docker images'* to check if the containers are running
  2. Go to your browser and navigate to *http://localhost:3000* to use the site
  3. If you want to see the database, download Robo 3T
  4. On startup, connect Robo 3T to port *localhost:27017* and you will be able to see all the users you create

### Technology Used

  1. HTML/CSS/JS
  2. Express
  3. React
  4. Node
  5. MongoDB
  6. Docker

### Features

  1. Account Creation
  2. Login Authentication with OAuth2.0 using Firebase
  3. Hosted on Server with DigitalOcean
  4. Maintaining State Across Logins

### License

MIT xPRO Full Stack Development Course (MERN Stack)
