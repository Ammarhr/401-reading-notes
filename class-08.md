### Routing 
**Routing** refers to how an application’s endpoints (URIs) respond to client requests. We can define routing using methods of the Express app object that correspond to HTTP methods like GET requests , POST requests also use app.all() to handle all HTTP methods and ``app.use()`` to specify middleware as the callback function.

These routing methods specify a callback function called when the application receives a request to the specified route (endpoint) and HTTP method, the application “listens” for requests that match the specified route(s) and method(s).

**EX:**
````
var express = require('express')
var app = express()

// respond with "hello world" when a GET request is made to the homepage
app.get('/', function (req, res) {
  res.send('hello world')
})
````````


### Route Middleware :
**Route middleware** in Express is a way to do something before a request is processed. This could be things like checking if a user is authenticated, logging data for analytics, or anything else we'd like to do before we actually spit out information to our user.
