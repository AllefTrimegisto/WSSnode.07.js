# WSSnode.07.js
#Utilizando o Node.JS e a biblioteca Express, crie um projeto inicial que tenha uma página com o texto “Hello World”.

const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send('Hello World');
});

app.listen(3000, () => {
  console.log('Server started on port 3000');
});
