# Shortly
URL shortner written in Angular, NodeJS, Express and Twitter Bootstrap with MongoDB database.

The URL Shortner is served up using a Node Express server.  

## Operation
To shorten URL links you must first create an account. Once your accoutn is created you can enter 
your favorite URL and click `Shorten` button. A shortened version of the URL will be created for
you. All of the URLs that you have shorten are saved in a MongoDB database so you can easily
log back into your account at a later date to retrieve the shorten URL.

Open the game in your browser. Decide whether you want to hit or stand based on the cards you have
been dealt. Once the player stands, the dealer plays. The winner is the player closest to 21 without
going over.

## Screenshots
Login Screen to Shortly
![Login Screen](http://jenniferbland.com/Shortly/screenshot-login.png)

Prompt to enter URLs to shorten
![Login Screen](http://jenniferbland.com/Shortly/screenshot-link-shortner.png)

List of URLs that have been shorten
![Login Screen](http://jenniferbland.com/Shortly/screenshot-shortened-links.png)

## Live Preview
[You can see this repo live here](http://jb-shortly-angular.herokuapp.com/#/signin).  The demo is hosted on Heroku.

## Installation
1. Download the repository
2. Run `npm install`
3. Launch your mongoDB if on local or make sure you connect to a mongoDB database if hosted outside of local
4. Launch Express server with `node index.js`
5. Create an account
6. Enter URLs to shorten


## Alternative Version
The original version of Shortly was written using an Express server and a Sqlite database.
[The Express version is here.](https://github.com/ratracegrad/Shortly-Expressy)
