# Personal-Blogging-Website
## A personal blogging website which will have a markdown using nodeJS, express and mongoDB.

to run the website type in terminal: "npm run devStart"

firt make sure that you install-
npm init -y
npm intall express mongoose marked slugify
npm i --save-dev nodemon (this makes sure the server is reloaded after every change in code)

This website helps a user to create new blogs, to edit already created blogs and to delete blogs

We use slugify to make the **title** of our blog into a path instead of a long ID.
We can see the slug in the url everytime a user clicks on a particular blog.

