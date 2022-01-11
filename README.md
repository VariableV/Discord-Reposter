<img src="repost.png?raw=true" width="75" align="left">

# Discord Reposter
Modified version of https://github.com/MysteryPancake/Discord-Reposter to post all non-bot messages in certain channels with ID of user.

## Setup
1. [Create your app with a Bot](https://discordapp.com/developers/applications/me).
2. Copy your bot's secret token and [paste it on this line](reposter.js#L9). Please don't leak your secret token on GitHub. If you're using Heroku, try to replace it with `process.env.SECRET_BOT_TOKEN` and setup the environment variable in Heroku.
3. Go to `https://discordapp.com/oauth2/authorize?client_id=<CLIENT_ID>&scope=bot`, with `<CLIENT_ID>` as your app's client ID.
4. [Install Node.js](https://nodejs.org/en/download): `brew install node`
5. [Install the dependencies](package.json#L36-L38): `npm install`
6. [Run the bot](reposter.js): `npm start`
7. Hope it works!
