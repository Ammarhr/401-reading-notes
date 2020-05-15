### Why would you want to run JavaScript code outside of a browser?
we need backend programming where our javascript code will interact with our database and can be used to create RESTful APIs.

### What is the difference between a module and a package?
- **Modules** are libraries for Node.js
Node.js has a simple module loading system. In Node.js, files and modules are in one-to-one correspondence.
**ex:**
Circle.js
Rectangle.js
Square.js

- **package** is one or more modules (libraries) grouped (or packaged) together. These are commonly used by other packages or a project of your own. Node.js uses a package manager, where you can find and install thousands of packages.
**ex:**
Shapes             <- Package name
  - Circle.js      <-
  - Rectangle.js   <- Modules that belong to the Shapes package
  - Square.js      <-

### What does the node package manager do? 
  **Node Package Manager (NPM)** is a command line tool that installs, updates or uninstalls Node.js packages in your application. It is also an online repository for open-source Node.js packages. The node community around the world creates useful modules and publishes them as packages in this repository.

  ### What is V8?
V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others. It implements ECMAScript and WebAssembly, and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors. V8 can run standalone, or can be embedded into any C++ application.

