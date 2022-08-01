
# [(MVC) The Tech Blog](https://github.com/mlarkin14/tech-blog)

## Description

  A CMS-style blog site similar to a Wordpress site, where developers can publish their blog posts and comment on other developers’ posts. This application is an example of the MVC paradigm in its architectural structure, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.
  
## Installation

Intialize node package manager and then run the following commands;  
`npm install express express-handlebars express-session sequelize mysql2 bcrypt connect-session-sequelize`


## Usage

 In order to use the application, first ensure that MySQL is installed in your environment.\
 Then, from the project root folder enter the sql shell and run the following command:\
`source db/schema.sql`\
Exit the sql shell and return to the command line still within your root project folder.\
Run the following commands:\
`npm run seed`\
`npm start`

### Link to the application running on Heroku: [The Tech Blog](https://glacial-fortress-10976.herokuapp.com/)
