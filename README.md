GreetingsJS
============

Simple AngularJS client for the GreetingsApp, a Spring web application providing a RESTFul JSON API consumed by this client. The GreetingsApp is available from [https://github.com/rogargon/greetingsApp](https://github.com/rogargon/greetingsApp).

GreetingsJS is running using GitHub Pages at [http://rogargon.github.io/greetingsJS](http://rogargon.github.io/greetingsJS) and consuming an instance of [GreetingsApp](https://github.com/rogargon/greetingsApp) running at [Heroku](http://greetings-app.herokuapp.com/api/greetings). 

To run locally, you need first node.js and its package manager (npm) installed.  You can get them from [http://nodejs.org/](http://nodejs.org/).

Then, use npm to install the dependencies in package.json, currently just the http-server module:
```
npm install
```

And to run the server on http://localhost:8000
```
npm run-script server
```

There is also a Procfile to run http-server once deployed to Heroku that calls npm start, which is intended just to run the application there.
