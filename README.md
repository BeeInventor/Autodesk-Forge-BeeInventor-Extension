# Autodesk-Forge-BeeInventor-Extension

## Setup

Visit [Autodesk Forge Portal](https://forge.autodesk.com/), sign up and create an app.
Then, use `http://localhost:3000/api/forge/callback/oauth` as the Callback URL, although it is not used on a 2-legged flow. In the end take a note of the Client ID and Client Secret.

### Create `.env` with following variables :

```sh
FORGE_CLIENT_ID=<<Your Forge Client ID>>
FORGE_CLIENT_SECRET=<<Your Forge Client ID>>
PORT_SERVER=3001
FORGE_CALLBACK_URL=http://localhost:3000/api/forge/callback/oauth
```

## Getting Start

To run the program locally, use the following command:

Install dependencies with:

```sh
npm install
```

Run locally :

```sh
npm start
```
