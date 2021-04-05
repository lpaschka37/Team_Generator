
# Team Generator


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
    

## Description

This is a Node CLI application designed to prompt the user for information about their team manager and then information about their team, before automatically generating a web page displaying the entire team's information.
      
## Table of Contents
1. [Install Instructions](#install-instructions)
2. [Usage Instructions](#usage-instructions)
3. [License](#license)
4. [Contribution Guidelines](#contribution-guidelines)
5. [Test Instructions](#test-instructions)
6. [Questions](#questions)

## Install Instructions

You will need [Node.js](https://nodejs.org/en/) to run this application, ensure Node.js is installed first.  

Lets get started, ensure the following files and folders are present in the root directory:   

* ```package.json``` (contains dependencies)

Next, open the integrated terminal and run the following command to install [Inquirer](https://www.npmjs.com/package/inquirer):

    npm install  

Once installed, confirm the folder ```/node_modules/inquirer``` is present before proceeding to Usage Instructions.

## Usage Instructions

Open an integrated terminal or bash command prompt and run the following command from the /develop directory:

    node app.js

Then answer each question to build your team. After adding a Manager, select Engineer or Intern to add a new member with that role. When you're finished, select 'Render'.

Your generated team.html file can then be found in the /output folder.

## Demo

<img src="" width="500" alt="application demo">

High-resolution video: 

## License
  
This application is licensed under MIT License.
     
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
    

## Contribution Guidelines

Contributors are welcome. This is open source software. Consider the people who will read your code, make sure it is formatted properly so this is easy to read for all potential users. 

## Test Instructions

Jest is required to execute tests. Current tests can be found in the /test folder. To run tests, open the terminal and run the following command:

    npm run test

Test results will be displayed in the terminal.

## Questions

If you have any questions, contact the author:  

GitHub [@lpaschka](https://github.com/lpaschka37)  
Email [lpaschka37@gmail.com](mailto:kylekleven8@gmail.com)