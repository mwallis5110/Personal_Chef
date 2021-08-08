# Title 
Sous Chef

## Description 
Sous Chef is a web application that allows a user to browse a recipe database and save recipes to their own user homepage/dashboard. From their homepage, they can access and delete recipes as they see fit.

## Table of Contents
#### [Installation Instructions](#installation-instructions)<br>
#### [Using The Program](#using-the-program)<br>
#### [License](#license)<br>
#### [How to Contribute](#how-to-contribute)<br>
#### [Tests](#tests)<br>
#### [Questions](#questions)<br>
#### [Github Link](#github-link)<br>
#### [Email](#email)<br>

## Installation Instructions
To initialize the program:
<ol>
 <li>Open program in an integrated terminal.</li>
 <li>Run "npm i" to install node dependencies.</li>
 <li>Create a database called "sous_chef_db" in MySQL Workbench or another visual database tool of your choice".</li>
 <li>Run "npm run seed" to seed the database with recipes.</li>
 <li>Run "nodemon server.js" to initialize the built-in server</li>
</ol>

## Using the Program
Sous Chef gives each user the ability to view and save recipes in their own dashboard.
<ul>
<li>Users must create an account using the "Sign Up" button located on the homepage. From there, they will be prompted to enter their username, email address and password.</li>
<li>If a user already has an account, they can log in using the "Log In" button on the homepage.</li>
<li>After logging in or signing up, users will be redirected to the main recipes page. This page shows every recipe available on our site.</li>
<li>Clicking on the "Save Recipe" button on any recipe will save that recipe to the user's "Saved Recipes" page</li>
<li>Clicking on the "Saved Recipes for (User)" button at the top of the page will redirect the user to their recipe dashboard, which contains all of their saved recipes. These recipes can also be deleted by clicking on the "Delete Recipe" button</li>
<li>Clicking on the "Logout" button at the top of the page will log the user out of their account.</li>
</ul>

## License
#### [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## How to Contribute
Create a separate branch, make your changes, and then open a pull request.

## Tests
No tests have been written for this program.

## Questions
Contact me via email at mwallis5110@gmail.com

## Github Link
https://github.com/mwallis5110/Sous-Chef

## Link to Deployed Site
https://sous-chef-project-2.herokuapp.com/

## Email
mwallis5110@gmail.com
  

#### This Readme was generated using a Node.js Readme generator. 
[Get that open-source generator here.](git@github.com:mwallis5110/Readme_Generator_HW_09.git)
