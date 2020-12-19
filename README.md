# basic-express-hosting
Express hosting basic code


You just gotta add this code to let express work. for repl


``` 
const express = require('express');
const app = express();
const port = 3000;

app.get('/', (req, res) => res.send('Hello World!'));

app.listen(port, () => console.log(`it works! `));

// ================= START BOT CODE =================== ```
Add this code to the begin. then download the package: express
`npm i express`
then get the url

https://project name.<ur repl account name>.repl.co
