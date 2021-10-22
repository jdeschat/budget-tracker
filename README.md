# Budget Tracker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
This application allows users to track their money even while offline. When transactions are made offline, the totals are updated when brought back online.

![alt text](https://github.com/jdeschat/budget-tracker/blob/main/assets/img/budget-tracker.png)

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributors](#contributors)
- [Tests](#tests)
- [Technology Used](#technology-used)
- [Questions](#questions)

## User Story
```
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```

## Acceptance Criteria
```
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```

## Installation

To install this application, clone the code into your terminal for the respective repository. Then, install npm by entering the command ```npm install```  into the terminal. This will install all dependencies in the ```package.json``` required to run this application.

## Usage
Run the following commands in the command-line in the root of the folder
1. npm install
2. npm start
3. Run the browser: http://localhost:3001/
4. In the "Name of transaction" field, enter the name of the transaction
5. In the "Transaction amount" field, enter the transaction amount
6. Click either "Add Funds" or "Subtract Funds" based on whether you would like to add or subtract those funds to your budget
7. Continue to add and subtract funds as you make transactions

## License
This application is rendered under MIT

## Contributors
To contribute to budget-tracker, clone this repo locally and commit your code on a separate branch.
  
Contributors:

<a href="https://github.com/jdeschat/budget-tracker/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=jdeschat/budget-tracker" />
</a>

Made with [contributors-img](https://contrib.rocks).

## Tests
![GitHub license](https://img.shields.io/badge/test-100%25-success)

## Technology Used
•	Javascript
•	Bootstrap
•	Node
•	HTML 
•	CSS
•	mongoose
•	express
•	manifest
•	morgan
•	compression

## Questions
My Github username is jdeschat, which can be accessed here https://github.com/jdeschat/budget-tracker.

This app is deployed through Heroku, which can be accessed here https://budget-tracker12.herokuapp.com/

You can reach me at jdeschat@gmail.com with additional questions.
