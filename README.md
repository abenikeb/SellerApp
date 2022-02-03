# Seller App
This Android version of the app is a marketplace for selling the stuff that vendor marketed product & contacting buyer and seller in a common 

## Table of contents
* [Introduction](#introduction)
* [Technologies](#technologies)
* [Setup](#setup)

## Introduction
This Android version of the app is a marketplace for selling the stuff that vendor marketed product & contacting buyer and seller in a common 

<!-- ![Software Developer](https://github.com/abenikeb/fetandelivery/blob/main/fetan_mock_2.png) -->
<img src="https://github.com/abenikeb/abenikeb/blob/main/Capture3.JPG" width="250" />

	
## Technologies
Project is created with:
* ⚛ React
* 📱 React Native
* 🖥 HTML, CSS & JS
* 🖥 Node JS 
* 💻 Mongo DB

## Setup

Make sure to follow all these steps exactly as explained below. Do not miss any steps or you won't be able to run this application.

### Install MongoDB

To run this project, you need to install the latest version of MongoDB Community Edition first.

https://docs.mongodb.com/manual/installation/

Once you install MongoDB, make sure it's running.

### Install the Dependencies

Next, from the project folder, install the dependencies:

    npm i

### Populate the Database

    node seed.js

### Run the Tests

You're almost done! Run the tests to make sure everything is working:

    npm test

All tests should pass.

### Start the Server

    node index.js

This will launch the Node server on port 3900. If that port is busy, you can set a different point in config/default.json.

Open up your browser and head over to:

http://localhost:3900/api/

You should see the list of items. That confirms that you have set up everything successfully.
