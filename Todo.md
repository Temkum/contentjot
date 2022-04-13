# Nodejs Express & MongoDB

- create server side apps with node/express/mongo
- Express framework to structure files, routes, middleware, modules, views
- mongoose for handling data models, passport for authentication, handlebars for views, and custom bars
- handling authentication with both Google OAuth and local
- make use of bootstrap4 and material js
- use heroku to deploy

## Content Jot

It's for content creators to register and jot down ideas for the next video. These ideas are not public, so only the user can see their own ideas.
In this project we mongoose(object data mapper to work with mongodb), express, passport

## StoryBooks

It's for creating public or private stories. Users can choose to allow or disable comments per story.
Uses google Oauth

- express, mongoose, passport
- google Oauth
- comments
- private, public stories
- helper functions
- momentjs
- materialize css

Mongoose is an object relational mapper. It's a way to interact with our database

After installation migrate to mongodb folder and run the following command `mongod --directoryperdb --dbpath C:\MongoDB\data\db --logpath C:\MongoDB\log\mongod.log --logappend --rest --install`

Then start the mongodb service `net start MongoDB`

We'll use mLab to store our db for deployment
Sign up for an account judekum14 : temjason22

Then sign up to heroku: judekum14: Temjason@22
Then install heroku CLI tool for easy login and deployment

- Next we'll create a package.json file to hold our dependencies `npm init` remember to attach a `--save` flag to append it to the file

- Now install express
- create our entry point

- to run our app use `node app` that's run node and our entry point that is app.js
