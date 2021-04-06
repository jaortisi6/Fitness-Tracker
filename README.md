# Fitness Tracker

## Description

This app is a fitness workout logger that takes in new exercises and uses MongoDB with Mongoose to log them to the database which can then be analyzed in the app's dashboard that has multiple graphic views of the different workouts.

## Installation

To install this application, first, branch the Github Repo and clone the repo to your local machine. Then, you will need to install the node dependencies which can be done by running the npm install command in your terminal/bash shell.

After the dependencies have been installed, you will need to populate your MongoDB database by uncommenting the required seed file or by running NPM Run Seed. Once filled in, you can start the server and use the program.

## Usage

Once the app has been installed, the application is run by entering "node server.js" or "npm start" in the terminal. After starting the app, the user should navigate to the local host URL for the port that is set up to host the application. 

Once loaded in the browser, users can either click the dashboard page to view the workout stats on the graphs provided or add/contnue a workout by clicking the buttons to add or update a new workout on the home page.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)