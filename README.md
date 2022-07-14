## What is this?
---

This is an example project from LearnHowToProgram.com that shows how to use the following tools to create a web app:

- React version 16
- Redux version 4
- Moment.js version 2
- Firebase verion 7
- React Router version 5

## Project Setup
---

### Create a Firebase project and Firestore database

Set up Firebase Firestore following the steps outlined [in this lesson](https://www.learnhowtoprogram.com/react/react-with-nosql/setting-up-a-firebase-project)

1. Create a Firebase account
2. Create a new project on Firebase
3. Create a new firestore database
4. Add Firebase to your web app

### Create a `.env` file with the Firebase configuration keys

Create a `.env` file (if you have not already), and use the details in your `firebaseConfig` to populate the following data. If you have misplaced this information, from the firebase console, click on the gear in the upper left of the page, then click project settings, and then scroll to the bottom of the page.

```
REACT_APP_FIREBASE_API_KEY = "YOUR-UNIQUE-CREDENTIALS"
REACT_APP_FIREBASE_AUTH_DOMAIN = "YOUR-PROJECT-NAME.firebaseapp.com"
REACT_APP_FIREBASE_PROJECT_ID = "YOUR-PROJECT-FIREBASE-PROJECT-ID"
REACT_APP_FIREBASE_STORAGE_BUCKET = "YOUR-PROJECT-NAME.appspot.com"
REACT_APP_FIREBASE_MESSAGING_SENDER_ID = "YOUR-PROJECT-SENDER-ID"
REACT_APP_FIREBASE_APP_ID = "YOUR-PROJECT-APP-ID"
```

### Enable authentication in your Firebase project

Set up Firebase Athentication following the steps outlined [in this lesson](https://www.learnhowtoprogram.com/react/react-with-nosql/firebase-authentication)

1. Navigate to your project in the firebase console, 
2. From the "Build" menu option, click on "Authentication"
3. Select the "Sign-in method" tab. 
4. Click on the option "Email/password." 
5. Then enable "Allow users to sign up using their email address and password." Don't enable "Email link".

### Install dependencies and run the project

1. Install dependencies by running `npm install` in the command line, in the root of the project folder.
2. Run the project by executing `npm run start` in the command line, in the root of the project folder.

## This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
---

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

### Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

#### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

#### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

#### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

#### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

#### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

#### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
