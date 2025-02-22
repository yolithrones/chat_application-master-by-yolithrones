# Realtime Chat Application

### [Live Site](https://realtime-chat-application.netlify.com)


![Chat Application](https://i.ytimg.com/vi/ZwFA3YMfkoc/maxresdefault.jpg)

## Introduction
This is a code repository for the corresponding video tutorial. 

In this video, we will create a full Realtime Chat Application. We're going to use  React on the front end, with NodeJS + Socket.io web socket library on the back end. 

By the end of this video, you will have a strong understanding of how to send and receive messages using web sockets and Socket.io to make any real-time application.



Setup:
- run ```npm i && npm start``` for both client and server side to start the development server

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).


# TaskMaster AI

TaskMaster AI is an AI-powered to-do manager built with **React and Node.js**. Designed to explore the capabilities of large language models (LLMs) without relying on specialized AI agent frameworks, it helps users manage tasks while delivering witty, sarcastic responses.

It leverages the **Gemini 1.5 Flash-002** model developed by Google.
This fast and versatile multimodal model supports an input context window of up to 1,048,576 tokens and can generate up to 8,192 tokens in a single request, making it highly efficient for diverse AI tasks. 
Best of all, access to the Gemini API is available free of charge through Google AI Studio and Vertex AI.

It also leverages [Socket.IO](https://socket.io) for real-time communication between clients and the server. Each client connection is assigned a unique `socket.id`, which is used to track individual sessions, including chat history and the current to-do state.

When a new client connects, a session is created and stored using their unique `socket.id`. This allows the server to manage personalized chat history and task data. When a client disconnects, its session is automatically removed.

## Features
- **Real-time task management:** Create, delete, categorize, and prioritize tasks.
- **AI-driven responses:** Enjoy humorous, sarcastic interactions while managing your to-dos.
- **Chat history & session management:** Each user connection is tracked individually for personalized interactions.
- **Global task storage:** Todos are shared across users (since no user authentication implemented yet).

## Tech Stack
- **Frontend:** React, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Real-time Communication:** Socket.IO
- **AI Model Integration:** Gemini 1.5 Flash-002

## 📦 Installation
### Clone the Repository
```bash
 git clone https://github.com/VPS010/TaskMaster-AI_Agent
 cd TaskMaster-AI_Agent
```

### Install Dependencies and run Backend and frontend
#### Backend
```bash
cd backend
npm install
```
#### Frontend
```bash
cd frontend
npm install
```

### Run the Application
#### Start Backend Server
```bash
cd backend
npm start
```
#### Start Frontend Client
```bash
cd frontend
npm run dev
```
Could also use docker-compose to start the mongodb container insted of using MongodbAtlas link in Backend.


This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

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
