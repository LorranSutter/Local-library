# Local Library

Tutorial from [Developer Mozilla](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website) to build a Local Library using [Express JS](http://expressjs.com/)

Part of BCDV1007 - Full Stack Development II from [Blockchain Development](https://www.georgebrown.ca/programs/blockchain-development-program-t175/) program from [George Brown College](https://www.georgebrown.ca)

## :runner: How to run

Open your terminal in the folder you want to clone the project

```sh
# Clone this repo
git clone https://github.com/LorranSutter/Local-library.git

# Go to the project folder
cd Local-library

# Install dependencies
npm install

# Run the project
npm start
```

If you want to use your own mongodb account, replace the following variable with your own mongo URL:

```sh
# Go to connectionDB.js
MONGOURI = <your-url>
```

Then you may populate your database using the following command:

```sh
node populatedb.js
```

## :book: Resources and technologies :computer:

- [Developer Mozilla](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Tutorial_local_library_website) - tutorial to build local library
- [Express.js](http://expressjs.com/) - web application framework
- [Pug](https://pugjs.org/api/getting-started.html) - template engine for Node.js and for the browser
- [MongoDB](https://www.mongodb.com/) - NoSQL database
- [Async](https://caolan.github.io/async/v3/) - library to perform asynchronous operations
- [Express validator](https://express-validator.github.io/docs/) - middleware to validate data
