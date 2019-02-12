# DiscordBot
A chat bot for discord app based off <a href="https://github.com/hydrabolt/discord.js/">discord.js</a>

# Features:
-google image search
-youtube streaming
-wikipedija
-meme engine...
!help for full features

# Installation

git clone and npm install

## Windows Users
Please note that you must have a working C compiler and Python in your path for
`npm install` to work. The bot has been tested to work on Windows using Visual Studio 2015 Community and Python 2.7, except for `!pullanddeploy`.
* [Installing Node on Windows](http://blog.teamtreehouse.com/install-node-js-npm-windows)
* [npm errors on Windows](http://stackoverflow.com/questions/21365714/nodejs-error-installing-with-npm)
* [Visual Studio Community 2015](https://www.visualstudio.com/en-us/products/visual-studio-community-vs.aspx)
* [Python 2.7](https://www.python.org/downloads/)

[Tuck 64 was kind enough to make a video walkthrough of the setup process](https://www.youtube.com/watch?v=H-82S2jFOII)

## RSS
You can create an rss.json file for feeds

## Special instructions for setting up google search and youtube APIs:

1) Create a Custom Search at: https://cse.google.com/cse/create/new

2) Leave the first line blank, and name the search engine anything you wish.

3) Click "Advanced Options" and then type ImageObject.

4) Hit create.

5) On this new page, enable the Image Search in the menu.

6) Then press "Search engine ID" under the Details header.

7) Copy this into the auth.json's "google_custom_search" section.

Make sure you also have your google server API key, which goes in the "youtube_api_key" section, or the search will fail.

# Running
Before first run you will need to create an `auth.json` file. A bot token or the email and password for a discord account are required. The other credentials are not required for the bot to run, but highly recommended as commands that depend on them will malfunction. See `auth.json.example`.

If you still need help join the legacy team on [discord.](https://discord.gg/m29GJBN)
# nodeJs-discord-bot
