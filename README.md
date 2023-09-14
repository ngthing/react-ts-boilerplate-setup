# Boilerplate project setup with React, TypeScript, React Router, Material UI


Set up enviroment with these:

- ✅ React & TypeScript
- ✅ React Router - to enable "client side routing" 
- ✅ Material UI - a library of React UI components that implements Google's Material Design.

Optional and not included in this set up but can be installed as [instruction below](#optional-and-not-included-in-this-setup):
- React Helmet - for multiple pages header
- React Redux  - state management library

(🌟 or 😍 means I found this very helpful)

The setup was created as the following: 

### Create a project with `create-react-app` 

To start a new Create React App project with TypeScript, you can run:
> `npx create-react-app [app-name] --template typescript` 

🥸 References: \
https://create-react-app.dev/docs/adding-typescript/  

### Then removed unrelated files come with the package. 

### Install Material UI

> `npm install @mui/material @emotion/react @emotion/styled @mui/icons-material` 

🥸 References: \
https://mui.com/material-ui/getting-started/installation/ 

If you want to create your own theme, you will need these: \
https://mui.com/material-ui/customization/theming/ \
https://m2.material.io/inline-tools/color/ \
https://zenoo.github.io/mui-theme-creator/ 😍 

### Install React Router 

Install react-router-dom since we are setting up for website. If you use React Native install react-router-native 

> `npm install react-router-dom@6`

🥸 References: \
https://reactrouter.com/en/main \
https://stackoverflow.com/questions/42684809/react-router-vs-react-router-dom-when-to-use-one-or-the-other 

#### Optional and not included in this setup: 
Install react-router, use it to cleanly customize title of any page on react app. 

> `npm i react-helmet-async`

🥸 References: \
https://www.freecodecamp.org/news/react-helmet-examples/ 🌟 \
https://www.npmjs.com/package/react-helmet-async 

Install React Redux if necessary
> `npm install react-redux` 

🥸 References: \
https://react-redux.js.org/introduction/getting-started \
https://redux.js.org/faq/general read this to determine when you need redux  