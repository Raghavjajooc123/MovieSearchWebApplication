
# Movie Central

This is a movie library web application which is created by using EJS, CSS, Javascript in the Frontend, Node.js for Backend, MongoDB as the Database, and Bootstrap to create the better user interface.

[movie-central](https://movie-central-heroku.herokuapp.com)

## Features

- User authentication(Sign In/Sign Up).
- Movie Search using OMDP API.
- Creating Playlist by adding movies.
- Displaying all playlists together
- View all movies of any playlist.


## Deployment

To deploy this project run

```bash
  npm run dev
```


## Demo

Register/Login Page :-

![ezgif com-gif-maker](https://user-images.githubusercontent.com/61447812/174406670-904cb2dd-8d83-47e8-85f1-922210fa1add.gif)

Search and display feature :-

![gif2](https://user-images.githubusercontent.com/61447812/174407840-546817f8-1096-4e01-8ffb-5badbf234640.gif)

Adding to playlist :-

![gif3](https://user-images.githubusercontent.com/61447812/174407708-95016f38-9ef0-44d5-a40f-ae6ab026b276.gif)

Viewing all playlists :-

![gif4](https://user-images.githubusercontent.com/61447812/174407812-d16f1b4c-25f4-4339-8b04-47ce25419cd4.gif)

## Hosting the project online

Install the Heroku CLI
Download and install the Heroku CLI.

Log in to your Heroku account and follow the prompts to create a new SSH public key.

```bash
  $ heroku login
```

Create a new Git repository
Initialize a git repository in a new or existing directory

```bash
$ cd my-project/
$ git init
$ heroku git: remote-a movie-central-heroku
```

Existing Git repository
For existing repositories, simply add the heroku remote
```bash
$ heroku git: remote -a movie-central-heroku
```

Deploy your changes
Make some changes to the code you just cloned and deploy them to Heroku using Git.

```bash
  $ git add .
  $ git commit -am "make it better"
  $ git push heroku master
```

