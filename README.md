# Challenge 14 Full-Stack React: Kanban Board

## Description

This is a Kanban board application that can be used to manage an individual or team's tasks. They can create, edit, complete & delete tickets. Users will have to log in to access the board. 


### User Story

```md
AS A member of an agile team
I WANT a Kanban board with a secure login page
SO THAT I can securely access and manage my work tasks
```

## Acceptance Criteria

```md
GIVEN a Kanban board with a secure login page
WHEN I load the login page
THEN I am presented with form inputs for username and password
WHEN I enter my valid username and password
THEN I am authenticated using JSON Web Tokens (JWT) and redirected to the main Kanban board page
WHEN I enter an invalid username or password
THEN I am presented with an error message indicating that the credentials are incorrect
WHEN I successfully log in
THEN a JWT is stored securely in the client's local storage for subsequent authenticated requests
WHEN I log out
THEN the JWT is removed from the client's local storage and I am redirected to the login page
WHEN I try to access the Kanban board page without being authenticated
THEN I am redirected to the login page
WHEN I remain inactive for a defined period
THEN my session expires, the JWT is invalidated, and I am redirected to the login page upon my next action
```

## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Test](#test)
  - [Questions](#questions)

## Installation
Make sure to install Node and express package.

## License
This application is covered under the MIT license.

## Usage
Use as described in licenses terms and conditions. 

## Test

The application will be invoked by using the following command:

```bash
npm run start
```

## Questions
    
If you have any questions, you can reach out to me via email at gretskyemily@gmail.com. 
Additionally, you can find more information on my GitHub page here: https://github.com/egretsky.
