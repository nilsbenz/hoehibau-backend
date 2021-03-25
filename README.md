# Höhibau Backend

This is a Strapi project which is deployed on Heroku.

## Development

Install the dependencies:

### npm install

Run the dev server:

### npm run develop

## Deployment

First, install the CLI:

### brew tap heroku/brew && brew install heroku

Then, log into Heroku:

### heroku login

Add Heroku as a git remote:

### heroku git:remote -a <project-name>

Push the current state to Heroku:

### git push heroku master
