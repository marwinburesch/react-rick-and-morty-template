# Rick & Morty App - with API and ReactRouter

![exercise cover](design/rick-and-morty-app-cover.png)

The goal of this exercise is to use ReactRouter as well as connect an external API to a React app 🎉!

Let's create an app using the [Rick and Morty API](https://rickandmortyapi.com/)

There are some wireframes in the `design` directory, an overview of the whole app with explanations, as well as an `.excalidraw` file. If you want to open the file, head to www.excalidraw.com, click the "Open" button and select it.

The features proposed in the design documents are:

| page          | url               | purpose                                                     |
| ------------- | ----------------- | ----------------------------------------------------------- |
| home          | `/`               | main page, welcome message, entry point                     |
| all caracters | `/characters`     | fetch and list characters (more button), each one clickable |
| one caracters | `/characters/:id` | character details, fetch more info (i.e. `/characters/1`)   |

BONUS:

- The all caracters page (`/characters`) can filter by `name` and/or `status`

## Tips

- Look at the wireframes and plan your approach. Smaller tasks are easier to finish
- Aim to work with branches, usually per component, per page, per task etc. Split work up into tasks
- Before you get started try to think about what some components could be and what they are supposed to do
- Every now and then, take some time to look at the bigger picture and which steps are coming up next

- Don't forget to change the CSS ruleset for `.App`, or feel free to remove it all together, and come up with your own naming convention

## Resources

## Git Guide

Here is an _example_ approach with git branches. Just as a guideline on how to split the whole project into smaller steps with corresponding branch names, to make it a bit easier for you to use git in this project. This is just _one_ way of doing it :)

1. Setup App (branchname: `setup`)
   - Install ReactRouter package
   - Add basic app structure (i.e. )

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
