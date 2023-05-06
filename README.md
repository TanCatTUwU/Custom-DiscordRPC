# Custom-DiscordRPC
A configurable Discord RPC
## Installation
1. Download [Nodejs](https://nodejs.org/en/) if you havent
2. Create an app on [Discord Developer Portal](https://discord.com/developers/applications)
   2.1 Copy client ID from OAuth2
4. Clone this repo then install requirements file, using:
   ```sh
   npm i
   ```
## Config
Since im too lazy to make a separate config file, you'll have to edit it inside 'Custom-DiscordRPC.js' file
```c
const clientId = 'insert client id here'; //Insert client ID of your Discord app
const title = '1st text'; // First text
const subtitle = '2nd text'; // Second text
const largeImg = 'large-default'; // Image that you upload on Rich Presence page on your app
const largeImgTxt= 'text appear when hover on img'; // Text that appear when you hover on image
const smolImg = 'small-default'; // Image that you upload on Rich Presence page on your app
const smolImgTxt = 'text appear when hover on small img'; // Text that appear when you hover on small image
```
## How to run
Open command prompt and type
   ```sh
   npm run rpc
   ```
