## Express Routing:
### Routing
Routing refers to how an application’s endpoints (URIs) respond to client requests.

### Using middleware
Express is a routing and middleware web framework that has minimal functionality of its own: An Express application is essentially a series of middleware function calls.

**Middleware** functions can perform the following tasks:

- Execute any code.
- Make changes to the request and the response objects.
- End the request-response cycle.
- Call the next middleware function in the stack.

**CRUD** Operations with REST and Express:

- **CREATE**: app.post('/resource')
- **READ**: app.get('/resource')
- **UPDATE**: app.put('/resource/:id')
- **DESTROY**: app.get('/resource/:id')

### The test pyramid :
**The test pyramid** is a way of thinking about how different kinds of automated tests should be used to create a balanced portfolio.

- **Units**: Server Internal Functions
- **Integration**: How it connects to other services
- **Acceptance**