# Anne's Model View Controller (MVC): MakeUp (Beauty) Blog


## Description.

Anne's Beauty Blog is Heroku deployed application, which serves as a CMS-style platform designed for Makeup lovers and professionals. It allows those in the Beauty communtiy to publish blog posts based on their thoughts and opinions. Additionally, the comment section below, allows users to interact and engage with another on Beauty posts. The application follows the MVC paradigm, using Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.
##### Note: The repository name is meant to reflect the name of the Rutgers University Coding Bootcamp Module (14) name convetion and 'not' the name of the Beauty Blog itself.

## Table of Contents:
- [Overview](#Overview)
- [The Challenge](#The-Challenge)
- [Usage Information](#Usage-Information)
- [Installation Process](#Installation-Process)
- [Built With](#Built-With)
- [What I Learned](#What-I-Learned)
- [Continued Development](#Continued-Development)
- [Author](#Author)


# Overview

## The Challenge:

The challenge of building this application involved creating a scalable and robust platform that could support multiple users, blog post and comments. The application was designed with security in mind, allowing users to authenticate themselves and protect their personal data. Furthermore, the application had to be built using modern web development technologies and follow best practices, including the MVC architecture pattern.

## Assigned User Story:
```
AS A developer who writes about tech
I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```
## Acceptance Criteria:
```
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the site for more than a set time
THEN I am able to view comments but I am prompted to log in again before I can add, update, or delete comments
```

## GIF:
### Figure.1 T

The following animation demonstrates the application functionality:
![gif](https://github.com/annemarywynter1986/MVC-Tech-Blog/assets/130412307/9a2fd287-c273-4b7b-b5b2-d89ade710d32)



## Usage Instructions:

#### Visit the homepage, "Login" or "Sign Up" for an account if you don't already have one.

1. Option: A) Account login: click on "login" in the navigation menu - enter Username and Password then click "Sign In" to proceed.
1. Option: B) Account Sign Up: click on "Sign Up" in the navigation menu - once open, enter Username, Email and Password then click "Sign Up" to proceed.
2. Once you have an account, you can create blog posts and comment on other users' posts.
3. Create a blog post: click on the "dashboard" option in the navigation menu and select "Create a New Blog Post."
4. Enter a title and contents for your Chess Blog Contribution, then click "Create Post" to save and publish.
5. View existing blog posts by clicking on "Home" in the navigation menu.
6. Comment: to view or "add a new comment" go to any blog post, click on any blog post - once open, you may view the comment history as well as add a new comments.
7. Edit or delete your blog post: click on the "dashboard" option in the navigation menu and select the post you wish to edit or delete.
8. Account Log out: click on "logout" in the navigation menu.

## Deployed Application Link:
https://radiant-fjord-05726-655a66c972dc.herokuapp.com/


## GitHub Repository:
https://github.com/annemarywynter1986/MVC-Tech-Blog.git


##  Walkthrough Video:
https://drive.google.com/file/d/19F7jvj7-BvlQDQcMAQhgRAKkHMOfjHSs/view?usp=sharing

## Screenshots:
![Screen Shot one](https://github.com/annemarywynter1986/MVC-Tech-Blog/assets/130412307/6f41b1fe-c3a6-471b-b43b-d8fc7d365f6c)
![Screen Shot two](https://github.com/annemarywynter1986/MVC-Tech-Blog/assets/130412307/486b649a-ea7c-40af-aeac-7e83863a6741)

![Screen Shot three](https://github.com/annemarywynter1986/MVC-Tech-Blog/assets/130412307/1bfec9c4-8f1c-46f4-8304-386177db80bf)

![Screen Shot four](https://github.com/annemarywynter1986/MVC-Tech-Blog/assets/130412307/f2ec60c0-1c12-4e33-a905-498fc27d6339)
![Screen Shot five](https://github.com/annemarywynter1986/MVC-Tech-Blog/assets/130412307/22d910e8-2ed1-46bd-a6b9-db50105963e8)





## Installation Process
1. Clone the Repository from GitHub 
(or) Download Zip Folder from Repository from GitHub
Open the cloned (or downloaded) repository in any source code editor.

## Built With:
- Saiyan Pride
- JSON:[ JSON](https://www.npmjs.com/package/json)
- Dynamic JavaScript
- Node.js [Version 16.18.1](https://nodejs.org/en/blog/release/v16.18.1/)
- Express.js:[Express.js](https://expressjs.com/en/starter/installing.html)
- Bcryptjs: [2.4.3](https://www.npmjs.com/package/bcryptjs)
- Connect Session Store using Sequelize: [7.0.4](https://www.npmjs.com/package/connect-session-sequelize)
- Dotenv: [8.6.0](https://www.npmjs.com/package/dotenv)
- Express: [4.17.1](https://www.npmjs.com/package/express)
- Express Handlebars: [5.2.0](https://www.npmjs.com/package/express-handlebars)
- Express-Session: [1.17.1](https://www.npmjs.com/package/express-session)
- Handlebars.js: [4.7.6](https://www.npmjs.com/package/handlebars)
- Node MySql2: [2.3.3](https://www.npmjs.com/package/mysql2)
- Sequelize: [6.29.3](https://www.npmjs.com/package/sequelize)
- License Badge: [Shields.io](https://shields.io/)
- Visual Studio Code: [Website](https://code.visualstudio.com/)

## What I Learned:
1. Implementing Model-View-Controller (MVC) architecture.
2. Creating and interacting with a MySQL database using Sequelize ORM.
3. Creating and using Express.js servers and routes.
4. Using Handlebars.js to create and display dynamic templates.
5. Implementing user authentication and password hashing with bcrypt.
6. Using Bootstrap for styling and layout.

### Continued Development:
1. Pagination for blog posts and comments.
2. Editing and deleting comments.
3. User profile pages.
4. Social media integration for sharing posts.


## Author

Anne Mary Wynter
