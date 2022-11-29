# Spoofy

> Une application Web pour visualiser les données Spotify personnalisées construites avec React, Express et l'API Spotify

Construit avec un tas de choses, mais pour n'en nommer que quelques-uns:

- [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
- [Create React App](https://github.com/facebook/create-react-app)
- [Express](https://expressjs.com/)
- [Reach Router](https://reach.tech/router)
- [Styled Components](https://www.styled-components.com/)

## Setup

1. [Enregistrez une application Spotify](https://developer.spotify.com/dashboard/applications) et ajoutez `http://localhost:8888/callback` comme URI de redirection dans les paramètres de l'application
1. Créez un fichier `.env` à la racine du projet basé sur `.env.example`
1. `nvm use`
1. `yarn && yarn client:install`
1. `yarn dev`
<!---
## Deploying to Heroku

1. Create new heroku app

   ```bash
   heroku create app-name
   ```

2. Set Heroku environment variables

   ```bash
   heroku config:set CLIENT_ID=XXXXX
   heroku config:set CLIENT_SECRET=XXXXX
   heroku config:set REDIRECT_URI=https://app-name.herokuapp.com/callback
   heroku config:set FRONTEND_URI=https://app-name.herokuapp.com
   ```

3. Push to Heroku

   ```bash
   git push heroku master
   ```

4. Add `http://app-name.herokuapp.com/callback` as a Redirect URI in the spotify application settings

5. Once the app is live on Heroku, hitting http://app-name.herokuapp.com/login should be the same as hitting http://localhost:8888/login
-->
