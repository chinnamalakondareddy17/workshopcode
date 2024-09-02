# Getting Started with Create React App

---

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# Workshop Demo

## Available Scripts

This is a simple React and Express-based application designed as a workshop demo. The application features a basic API using Express, which serves an array of names to a React frontend. The frontend displays these names with some interactive styling effects.

In the project directory, you can run:

## Table of Contents

### `npm start`

- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Features](#features)
- [License](#license)

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Installation

The page will reload when you make changes.\
You may also see any lint errors in the console.

1. **Clone the Repository:**

### `npm test`

```bash
git clone https://github.com/yourusername/workshop-demo.git
cd workshop-demo
```

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information. 2. **Install Dependencies:**

### `npm run build`

```bash
npm install
```

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

## Running the Application

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### Development Mode

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

1. **Start the Express Server:**

### `npm run eject`

```bash
npm run dev
```

**Note: this is a one-way operation. Once you `eject`, you can't go back!**
This will start the Express server using `nodemon`, which automatically restarts the server on code changes.

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project. 2. **Start the React Application:**

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.
Open a new terminal and run:

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

```bash
npm start
```

## Learn More

This will start the React development server.

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started). 3. **Access the Application:**

To learn React, check out the [React documentation](https://reactjs.org/).
Open your browser and navigate to `http://localhost:3000` to view the React app.

### Code Splitting

## Project Structure

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

```bash
├── public
│   ├── index.html
│   └── ...
├── src
│   ├── App.css
│   ├── App.js
│   ├── index.js
│   ├── server.js
│   └── ...
├── package.json
└── README.md
```

### Analyzing the Bundle Size

- **`public/`**: Contains the public assets of the React app.
- **`src/`**: Contains the source code for both the React frontend and the Express backend.
  - **`App.js`**: The main React component that fetches and displays the names.
  - **`App.css`**: Contains the styling for the React app.
  - **`index.js`**: The entry point for the React application.
  - **`server.js`**: The Express server file that handles the API requests.
- **`package.json`**: Contains the project metadata and dependencies.
- **`README.md`**: Provides an overview and setup instructions for the project.

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

## Dependencies

### Making a Progressive Web App

- **React**: A JavaScript library for building user interfaces.
- **Express**: A minimal and flexible Node.js web application framework.
- **Nodemon**: A utility that monitors for changes in your code and automatically restarts your server.
- **Cors**: A package to provide a Connect/Express middleware that can be used to enable CORS with various options.

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

## Features

### Advanced Configuration

- **Express API**: Serves a list of names via an endpoint.
- **React Frontend**: Fetches and displays the list of names with hover effects.
- **Dynamic Styling**: Interactive UI with CSS transitions and transformations.

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

## License

### Deployment

This project is licensed under the MIT License.

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
