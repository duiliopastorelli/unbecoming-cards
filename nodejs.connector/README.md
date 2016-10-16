# unbecoming-cards - NodeJS connector

## Contribute
The best way to contribute is by submit a pull request on git:
https://github.com/duiliopastorelli/unbecoming-cards/

Every contribution is welcome! :)

### Local environment setup

In order to start the app you need Node.js installed in your local machine: https://nodejs.org/

Then you need npm for all the dependencies management:

```$ npm install npm -g```

Enter into the repository folder and run:

```$ npm install```

This command will install all the dependencies required in order to run the application on you local machine.

### Develop with debugger

To start the application in debug mode run:

```$ DEBUG=unbecoming-cards:* npm start```

And visit this address on your browser: http://127.0.0.1:3000/

This will allow you to see in the terminal a lot of messages that are unavailable in prod.

We suggest you to install also nodemon and node-inspector. These are 2 valuable tools that make your life much easier.

#### Nodemon

```$ sudo npm install -g nodemon```

Nodemon is a wrapper that restart your app every time it spots a change in one of your local file. This command will then start the application INSIDE this useful wrapper and enable the debug listener (useful for node-inspector):

```$ npm run dev```

#### Node Inspector

Node inspector helps in node debugging. Install it with:

```$ sudo npm install -g node-inspector```

Then run the inspector with:

```$ node-inspector```

Visit http://127.0.0.1:8080/?port=5858 and in another terminal run the server with Nodemon:

```$ npm run dev```

Then in another browser tab visit http://127.0.0.1:3000/test

Now you're able to use breakpoints and debug the app from the node-inspector browser tab and interact with the app in the other browser tab.