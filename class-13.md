###  Bearer Authentication:
**Bearer authentication** (or token authentication) is an HTTP authentication scheme that involves security tokens called bearer tokens. The name **“Bearer authentication”** can be understood as “give access to the bearer of this token.”

### JSON Web Token:
- **JSON Web Token (JWT)** is an open standard that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. 
- **JWTs** can be encrypted to also provide secrecy between parties, we will focus on signed tokens.

### Uses  Of JSON Web Tokens:
- **Authorization:** Once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token.
- **Information Exchange:**  JSON Web Tokens are a good way of securely transmitting information between parties.

### JSON Web Token structure?
In its compact form, JSON Web Tokens consist of three parts separated by dots (.), which are:

- Header
- Payload
- Signature

