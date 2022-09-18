# Team-Profile-Generator
License Badge Top Language

A Node command-line application that uses inquirer and takes in information about employees and generates an HTML webpage that displays summaries for each person.

Installation
Download or clone repository
Node.js is required to run the application
npm install to install the required npm packages
Usage
Application will be invoked by using the following command:

node app.js

The user will be prompted for information to select employee type

Manager (only one is allowed to be added)
Engineer (any number)
Intern (any number)
All employee will be asked the following information, all prompts are validated to ensure appropriate input to generate the correct output

Name
ID
Email
Depending on employee role, additional prompts are presented

Manager - office number
Engineer - GitHub username
Intern - school
Then a team.html page will be generated in the output directory, that displays a nicely formatted team roster.
<img width="813" alt="ScreenShot of deployed application" src="https://user-images.githubusercontent.com/104540828/190929793-ee125726-cd1e-488a-9fa0-bb3fe69f80b1.png">
This is a sample Team page for a project generated using this application

LINK TO DEPLOYED APPLICATION
https://drive.google.com/file/d/1ouhP5gJQ31NU6XlVvFe5CEExa2HtR9oI/view

Features
JavaScript
Node.js
jest
npm
License
Copyright (c) Mengmei Tu. All rights reserved.

Licensed under the MIT license.
