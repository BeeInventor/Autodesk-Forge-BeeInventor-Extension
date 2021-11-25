# Autodesk-Forge-BeeInventor-Extension

![demo](https://github.com/BeeInventor/Autodesk-Forge-BeeInventor-Extension/blob/main/bee-extension.gif)

## Setup A VIewer

Visit [Autodesk Forge Portal](https://forge.autodesk.com/), sign up and create an app.
Then, use `http://localhost:3000/api/forge/callback/oauth` as the Callback URL, although it is not used on a 2-legged flow. In the end take a note of the Client ID and Client Secret.

## Create Environtment with Following Variables :

```sh
FORGE_CLIENT_ID="Your Forge Client ID"
FORGE_CLIENT_SECRET="Your Forge Client ID"
PORT=3000
FORGE_CALLBACK_URL=http://localhost:3000/api/forge/callback/oauth
```

## Getting Started

To run the program locally, use the following command:

Install dependencies with:

```sh
npm install
```

Run locally :

```sh
npm start
```

## Full Documentation and A Guidance How to Use The Tools :

1. [doc](https://docs.google.com/document/d/1TAR6bxoDlj344Ef48qYd7VDcqN_ZU37GQvCLsYRlTtM/edit?usp=sharing)
2. [live demo](https://forge-bee-website.vercel.app/)
