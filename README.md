# Task Tracker React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and the Maim branch is deployed with [Netlify.com](https://www.netlify.com/) at [https://qsturner-react-task-tracker.netlify.app/](https://qsturner-react-task-tracker.netlify.app/)

## Overview
This web app was created by following a tutorial on YouTube ([source](https://www.youtube.com/watch?v=w7ejDZ8SWv8&t=4092s)). 

The web app is a task tracker, which allows the user to set and delete tasks, also adding a date and time to each task as well. It takes advantage of the REACT framework's flexibility and responsiveness to edit components on the page without having to reload.

### Main Branch
The Main branch does not have a backend, as the task data is stored in the root file, [App.js](https://github.com/QSturner/taskTrackerReactApp/blob/main/src/App.js), and passed through the relevant components as props. This means that once the page is reloaded, all data is reset to its initial state.

### Backend Branch
The Backend branch simulates getting, posting, and putting data into and from a RESTful API. This branch utilizes [JSON Server](https://www.npmjs.com/package/json-server), a fake API where data is stored in a JSON file locally.
