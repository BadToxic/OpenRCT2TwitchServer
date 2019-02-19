# OpenRCT2 Twitch Server

## Description

The *OpenRCT2 Twitch Server* is a server software for self-hosting the Twitch integration server for OpenRCT2.  
By default, the game tries to use the server on *openrct.ursalabs.co*, which is down now. With this programme you can host your own server to reenable the Twitch integration for OpenRCT2.
This is a version modified by BadToxic to improve some functions.

## Instructions

(You can either use your user account for this or, better, create a new Twitch user as bot account.)

1. Get an **OAuth token** eg. from https://twitchapps.com/tmi/
![Twitch Chat OAuth Password Generator](/img/twitch-chat-oauth-password-generator.png)

2.1. Create an App on the twitch developers site https://glass.twitch.tv/console
2.2. After creating you get your **client id** of your twitch app.
![Twitch Dev-Portal: Client id](/img/twitch-dev-portal-app-client-id.png)

3. Copy `config/config.json.default` to `config/config.json` and change at least the **name** and enter the **OAuth** token and the **client id**.  

4. Set your server's API URL in OpenRCT2's options. Default: http://localhost:11780
![Twitch-API-URL](/img/twitch-api-url.png)

5. Start the server with [Node.JS](https://nodejs.org): `node OpenRCT2TwitchServer.js`.

6. Activate the twitch integration in the in game menu.
![Activate Twitch-Integration](/img/activate-twitch-integration.png)

Now you can use all of the Twitch integration features. Have fun seeing your viewers walking through your park again!

## New Features

Coming soon...
