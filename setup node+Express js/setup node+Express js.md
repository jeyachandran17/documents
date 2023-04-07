
### Setup Express js

1. Go to empty folder or create empty folder
2. create a file named ``` index.js ```
3. ``` npm init -y ``` this commend will create package.json
4. ``` npm i express ```  this commend will installs express
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
- Goto to ``` http://localhost:4000 ``` to see the `Express server has successfully working✨✔` message.

- `Congratulations. finally you are created a server 🎉🎉`

### Manually restart the server

1. ``` node index.js ``` - Start server
2. Press keys to ``` ctrl + c ``` - Stop server

