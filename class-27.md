## React Testing:

- **Snapshot tests** are a very useful tool whenever we want to make sure our UI does not change unexpectedly.
-  Make assertions on the exact rendered markup at any state of the application.
- **Render Testing:** allows for jQuery-like inspection of the virtual DOM tree.
- **Shallow Testing:** Executes and renders the called/container component, but does not compose children.
- **Mounting:** Executes the full component and children. Allows for inspection of rendered Virtual DOM as well as the current state



### React Deployment  
The node server is only there to aid in your development. ``$ npm run build``

#### Github pages deploy
- Create an empty repository on GitHub.
- Create a new React app on your computer.
- Install the gh-pages package as a "dev-dependency" of the app.
- Create a git repository in the app's folder.
- Optionally, commit your source code to the "master" branch and push your commit to GitHub.
