# FavNote - backend

This is a backend of FavNote app. Here is the connection with MongoDB database created using Express framework. Backend was created based on [eduweb.pl](https://eduweb.pl/sciezki/react) React course.

See more about FavNote app [here](https://github.com/sawicka/favnote)

## Technologies

- Express: 4.17.1
- Mongoose: 5.9.25,

## Features

- fetch all notes from database
- show all information about choosen note
- add note
- delete note

## To do

- register user
- login
- logout

## Setup

First steps are the same as in frontend of this app. Click [here](https://github.com/sawicka/favnote) to check them.
Create a database and add 2 collections: notes and users.
Notes attributes: type, title, content, articleUrl, twitterName and userId.
Users attributes: username, password.
Create file .env and add a global constant `NODE_DATABASE=...` where you save your connection string.

## Licens

MIT
