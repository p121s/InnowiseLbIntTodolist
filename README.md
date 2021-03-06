# Innowise Lab Internship: Level 1: Clever to-do list

The technical specification is [here](https://docs.google.com/document/d/1heFuihWrsw14bCpUdr6fla9ysqE6IrsobSMKAOpBiKA/edit).

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Additionally used

- Firebase [Operation and installation instructions](https://firebase.google.com/)
- React-router [Operation and installation instructions](https://reactrouter.com/)
- Eslint [Operation and installation instructions](https://www.npmjs.com/package/eslint)
- Prettier [Operation and installation instructions](https://www.npmjs.com/package/prettier)

## Folder structure

### `src`

    - conponents
        - caledar
            - day
                - Day.js
                - Day.scss
            - Calendar.js
            - Calendar.scss

**Contains calendar components**

-----

    - conponents
        - formInpt
            - FormInput.js
            - FormInput.scss

**Contains an input component for data entry**

-----

    - conponents
        - pages
            - LogInPage.js
            - LogInPage.scss
            - RegistrationPage.js
            - TasksPage.js
            - TasksPage.scss

**Contains page components**

-----

    - conponents
        - toDoList
            - itemTask
                - ItemTask.js
            - CreatingEditingPage.js
            - CreatingEditingPage.scss
            - ToDoList.js
            - ToDoList.scss

**Contains task components**

-----

    - constants
        - Constants.js

**Contains constants for the application**

----

    - fireBase
        - FireBaseInitialization.js

**Contains the firebase initialization file**

-----

    - modalMessages
        - ModalMessages.js

**Contains a modal message settings file**

-----

    - routing
        - ModalSwitch.js

**Contains a route switch for the application**

-----

    - transliteFunction
        - Translite.js

**Contains a transliteration function for input components**

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

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
