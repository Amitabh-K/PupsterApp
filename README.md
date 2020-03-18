# Pupster App

## Brief

* This app contains 3 routes:

    1. `/about`: A static welcome screen for visitors to the application.

    2. `/discover`: This page displays a photo of a random dog retrieved from the [Dog Ceo API](https://dog.ceo/dog-api/). This page contains 2 clickable buttons: one for passing or "thumbs-downing" a dog, and one for picking or "thumbs-upping" a dog. When either button is clicked, a new dog image is loaded from the API. If you "thumbs up" a dog, there is a 1 in 5 chance that the dog likes you too, and the friends count goes up by 1.

    3. `/search`: This page allows you to search the [Dog Ceo API](https://dog.ceo/dog-api/) for all dogs by breed. After a search is made, a list of all of the results appears underneath.

* The Pupster app has implemented each of these three pages and their basic functionality, 

* This Pupster app displays a navigation bar that is present on every route.



* Utilized documentation of the followings: 

  * [Axios](https://github.com/mzabriskie/axios)
  
  * [React Router](https://reacttraining.com/react-router/web/guides/philosophy)

  * [React](https://facebook.github.io/react/docs/hello-world.html)

  * [Dog Ceo](https://dog.ceo/dog-api/)


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
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

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
