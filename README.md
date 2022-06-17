
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

Here is a link to the gif file of the outcome:-

[![Demo CountPages alpha](https://drive.google.com/file/d/1Au5RVmtD3RhspxIvAVNZZk5kf0V8lq6j/view?usp=sharing.)](https://drive.google.com/file/d/17kT8hFyLfgDGhMQa8G40BznJSzan4IAK/view?usp=sharing)


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

