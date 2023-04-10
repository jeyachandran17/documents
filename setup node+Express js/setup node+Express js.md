
### Setup Express js

1. Go to empty folder or create empty folder
2. create a file named `index.js`
3. `npm init -y` this commend will create package.json
4. `npm i express`  this commend will installs express
5. Pasted the below sample code in `index.js`
```
const express = require("express");
const app = express();

const PORT = 4000; //you are change the port number is possible

app.get("/", function (request, response) {
  response.send("Express server has successfully working✨✔ ");
});

app.listen(PORT, () => console.log(`The server started in: ${PORT} ✨✨`));


```
6. Goto to `http://localhost:4000` to see the `Express server has successfully working✨✔` message.

7. `Congratulations. finally you are created a server 🎉🎉`

### Manually restart the server

1. `node index.js` - Start server
2. Press keys to `ctrl + c` - Stop server

### Automatic restart of server

1. Autometic restart the server to use `nodemon`
2. Install nodemon commend - `npm install --save-dev nodemon`
3. `--save-dev` flag is mentioned since `nodemon` is only be needed for development


### Its like shortcut to run commands

1. add the two line on `scripts` "start" & "dev" in `package.json` 

```

{
  "scripts": {
    "start": "node index.js", // helps in heroku deployment
    "dev": "nodemon index.js" // shortcut to run nodemon
  }
}

```
### Start the Terminal commands
1. npm run start or npm start (shortcut) -> to run/start the app
    - `npm run dev` -> to dev mode

2. Dev mode automatically listens to changes you make and restarts the server

3. Latest Import & Exports
    - just added one line "type" in `package.json`
```

{
  "type": "module", // to support latest import & export syntax
  "scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js"
  }
}

```
```

{
  "type": "commonjs", // older require & module.exports syntax
  "scripts": {
    "start": "node index.js",
    "dev": "nodemon index.js"
  }
}

```
4. index.js with latest import syntax
```

// const express = require("express"); // "type": "commonjs"
import express from "express"; // "type": "module"
const app = express();

const PORT = 4000;
app.get("/", function (request, response) {
  response.send("Express server has successfully working✨✔");
});

app.listen(PORT, () => console.log(`The server started in: ${PORT} ✨✨`));

```

### Added the mongo db with Express js

1. install the package - `npm i mongodb`
2.  Pasted the below sample code in `index.js`

```

// const express = require("express"); // "type": "commonjs"
import express from "express";
import { MongoClient } from "mongodb"; // "type": "module"

const app = express();
const PORT = 4000;

const MONGO_URL = "mongodb://127.0.0.1";
const client = new MongoClient(MONGO_URL); // dial
// Top level await
await client.connect(); // call
console.log("Mongo is connected !!!  ");

app.use(express.json());

app.get("/", function (request, response) {
  response.send("Express server has successfully working✨✔");
});

app.listen(PORT, () => console.log(`The server started in: ${PORT} ✨✨`));

```

### add cors

1. install the package - `npm i cors`
2. It's used to help share the data's 
3. Pasted the below one code in `index.js`
```
app.use(cors());
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h3 style="text-align: center; font-family: cursive;">Thank you..🙏🙏</h3>
</body>
</html>