# Todo Web App

Welcome to the Todo Web App! This project is a task management application built with Firebase for the backend and a static frontend. The application allows users to manage tasks, view a calendar, and authenticate using Firebase Authentication.

## Table of Contents

- [Features](#Features)
- [Technologies Used](#Technologies-Used)
- [Usage](#Usage)
- [Contributing](#Contributing)
<!-- 
- [Setup and Installation](#setup-and-installation)
- [Environment Variables](#environment-variables)
- [Deployment](#deployment)
- [License](#license)
-->

## Features

- User Authentication with Firebase
- Task Management (Add, Update, Delete)
- Calendar View
- Real-time Data Sync with Firestore

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Firebase (Firestore, Authentication)
- **Build Tool**: Webpack
- **Hosting**: GitHub Pages

**Clone the repository**:
   ```bash
   git clone https://github.com/TANUJ-BISHT/Todo-App.git
   cd Todo-App
   ```
<!--
## Setup and Installation

## Webpack Configuration Setup

1. **Install Webpack and Webpack CLI**:
   ```bash
   npm install webpack webpack-cli --save-dev
2. **Create a webpack.config.js file**:
```js
const path = require('path');

module.exports = {
  entry: './src/index.js',
  output: {
    filename: 'bundle.js',
    path: path.resolve(__dirname, 'dist')
  },
  module: {
    rules: [
      {
        test: /\.css$/,
        use: ['style-loader', 'css-loader']
      }
    ]
  },
  mode: 'development'
};
```
3. **Update package.json scripts**:
```json
"scripts": {
  "build": "webpack"
}
```
-->

## Usage
1. **Build the project**:
```bash
npm run build
```
2. **Start the development server**:
```bash
npm start
```
3. Open your browser and navigate to ``http://localhost:8080`` to view the application.

## Contributing
Feel free to open issues or submit pull requests.

## Note
"This is my first web app, so there may be some issues."
