# Real-Time Collaborative Whiteboard

## Overview
The Whiteboard Project aims to create a digital whiteboard application that allows users to collaborate in real-time, share ideas, and brainstorm effectively.

## Features
- Real-time collaboration
- Drawing tools (pen, highlighter, shapes)
- Text tools (text boxes, fonts)
- Image upload and manipulation
- User authentication and roles
- Saving and loading whiteboard sessions
- Exporting whiteboards as images or PDFs
- Integration with other collaboration tools (e.g., Slack, Microsoft Teams)

## Technologies
- Frontend: React, Next.js
- Backend: Node.js with WebSocket (Socket.IO), Express
- Database: MongoDB
- Authentication: JWT, OAuth


## Setup Instructions

1. **Clone the repository:**
    ```bash
    (https://github.com/krinishita-1602/Real-Time-Collaborative-Whiteboard.git)
    cd whiteboard
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Run the development server:**
    ```bash
    npm run dev
    ```

4. **Build the project:**
    ```bash
    npm run build
    ```

5. **Start the production server:**
    ```bash
    npm start
    ```

## Deployment Instructions

1. **Build the project:**
    ```bash
    npm run build
    ```

2. **Deploy to GitHub Pages:**
    ```bash
    npm run deploy
    ```

## Scripts

- `dev`: Runs the development server with `nodemon` for hot-reloading.
- `dev:client`: Runs the client-side code with `ts-node`.
- `build:server`: Compiles the server-side TypeScript code.
- `build:next`: Builds the Next.js application.
- `build`: Runs all build-related scripts.
- `start`: Sets the `NODE_ENV` to production and starts the server.
- `lint`: Runs the Next.js linter.
- `predeploy`: Runs the build script before deploying.
- `deploy`: Deploys the project to GitHub Pages.



---


#
