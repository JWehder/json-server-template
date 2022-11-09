# JSON Server - Dream Team Fantasy Football

This database serves as a backend for my application [Dream Team Fantasy Football](https://github.com/JWehder/phase-2-project). If you haven't already, fork and clone the files there. 

## Frontend Installation

Fork and clone the files within [this repository](https://github.com/JWehder/phase-2-project) to get started. If you are unsure of how to fork and clone repositories from GitHub, click [here](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop). Once you have it downloaded, open this directory in an IDE of your choice. 

Before you get started, run the following in your terminal to install the dependencies for this project.

```sh
npm install 
```
Thereafter, run the below in your terminal.

```sh
npm start
```

## Setup

Fork and clone this repo. Then install the dependencies by running:

```sh
npm install
```

## Seeding Data


Run `npm run seed` to copy data from the `db/seeds.json` file to the
`db/db.json` file. `json-server` uses the `db.json` file to create your RESTful
API, so make sure your `db.json` file is always up to date!

Any time you want to reset your database back to your original data, run
`npm run seed` again. Doing this will overwrite all the data in your `db.json`
file, so make sure you don't have any data in that file that you don't mind
losing!

## Running the Server Locally

To run your server in development mode, run:

```sh
npm run dev
```

While running in development mode, the server will re-load any time you make
changes to the `db.json` file, so you can test our your seed data.

While your server is running, you can make requests to
[http://localhost:3000](http://localhost:3000). Check it out in the browser to
make sure your server works!

## Deploying the Server

Free services like Heroku make it simple to deploy your Node server. Heroku also
works nicely with Rails, which you'll learn later in the program.

First, download the [Heroku CLI](https://devcenter.heroku.com/articles/getting-started-with-nodejs#set-up).

Then, [deploy your app](https://devcenter.heroku.com/articles/getting-started-with-nodejs#deploy-the-app).

Since Heroku deployment integrates with your git repo, you can easily deploy
changes to your database. To deploy changes, make sure to commit your code:

```sh
git add .
git commit -m "Updated database"
```

Then push your main/default branch up to Heroku:

```sh
git push heroku main
```

## License

[MIT](https://choosealicense.com/licenses/mit/)