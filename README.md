# Web-server with Express and Nodejs

***Features***

***process.env.PORT*** makes the app dynamic so that it can run any port assigned to it in the future when hosted on a live server.

The ***normalizePort*** function returns a valid port, whether it is provided as a number or a string.

The ***errorHandler*** function checks for various errors and handles them appropriately — it is then registered to the server.

A listening event listener is also registered, logging the port or named pipe on which the server is running to the console.

Requirements
-----------
* Install nodejs and npm
* Install Express
* Install nodemon

