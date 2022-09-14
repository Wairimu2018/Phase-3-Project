     About • Features • Working Demo • How it works 

This is an app with search and filtering tools that enable users to build and bookmark grocery lists for meal prepping.

# Features 
                                    Ruby on rails
# Working Demo
[![Screenshot-from-2022-09-14-22-40-35.png](https://i.postimg.cc/KY7q5k0B/Screenshot-from-2022-09-14-22-40-35.png)](https://postimg.cc/8F5mp5Qz)

# Requirements
1. Access a Sqlite3 database using Active Record.
2. You should have a minimum of two models with a one to many relationship.
3. You should build out a simple React frontend to give your user 3 of the 4 CRUD abilities for at least one of your resources. For example, build out a todo list. A user should be able to create a new todo, see all todos, update a todo item, and delete a todo. Todos can be grouped into categories, so that a todo has many categories and categories have many todos.
4. Use good OO design patterns. You should have separate classes for your models.

# Getting Started
Clone down this repository. A basic Rack app is located in the backend folder.

First, cd into the backend folder

# run
                             bundle install 
in your backend folder to install your gems.


The app/application.rb file has an example GET route. Replace this route with routes for your project!

Start your server with:

shotgun --port=9292
Note: This will run your server on port http://localhost:9292. shotgun is a ruby gem that will automatically reload your Rack server. You may still need to refresh your browser to see changes.

Your backend and your frontend should be in two different repositories. Create a new repository in a separate folder with a React app for your frontend using create-react-app.

Fetch Example
Your React app should make fetch requests to your Rack backend! Here's an example:

fetch("http://localhost:9292/test")
  .then((res) => res.json())
  .then(console.log);
