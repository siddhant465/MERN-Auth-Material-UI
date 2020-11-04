# MERN Authentication with Material UI

A MERN authentication application which leverages Material UI's design components and Redux for state management.

Live Demo on Herkou: https://mern-auth-materialui-465.herokuapp.com/

## Getting Started

- First, clone this repository and add a "keys.js" file in the "config/" directory with the following contents:

```js
module.exports = {
  mongoURI: "<Your MongoDB Atlas Connection String>"
  secretOrKey: "<Your Secret Key>",
};
```

- Then run `npm install` in the main directory, as well as the "client/" directory to install the node modules.

```bash
npm install && cd client/ && npm install
```

- Finally, run `npm run dev` to start the server and client concurrently.

```bash
// Server -> http://localhost:5000 & Client -> http://localhost:3000
npm run dev
```

I've used the free React templates that are available on Material UI (https://material-ui.com/getting-started/templates/) for the front-end. You can build off of these or make the appropriate changes to develop your project.

### Credits

This app is largely based on Brad Travery's (https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA) MERN Stack tutorial and the following Medium Article by Rishi Prasad (https://blog.bitsrc.io/build-a-login-auth-app-with-mern-stack-part-1-c405048e3669).
