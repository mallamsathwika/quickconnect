# Video Chat Application


This application provides a user-friendly interface that allows users to initiate video calls. Users can connect with family, friends, colleagues, or strangers, depending on their privacy settings and preferences. The application typically offers features such as one-on-one video calls, group video calls, and instant messaging, during the chat session using Google authentication

This application is built using the PeerJS library, socket.io and Node.JS library for managing the server. The design for this project is inspired by Google Meet and would look to improve both design and utility in the near future. 

## Table of Contents


- [Features](#features)
- [Prerequisites](#prerequisites)
- [Technologies Used](#technologies-used)
- [Setup](#setup)


## Features

- Real-time video conferencing - Users can organize meets where others could join using the meet ID.
- User authentication using Gmail-id and session management.
- Chat functionality - where users can chat with others during video calls.
- Light/dark mode toggle feature for enhanced user experience.


## Prerequisites

Install [node.js](https://nodejs.org/en/) in your machine

## Technologies Used

- [WebRTC](https://webrtc.org/): A free, open-source project that provides real-time communication capabilities via APIs for voice, video, and data transfer.
- [SocketIO](https://socket.io/): A JavaScript library that enables real-time bidirectional communication between clients and servers using WebSockets.
- [PeerJS](https://peerjs.com/): A library that simplifies WebRTC peer-to-peer data, audio, and video calls by providing a simple API and handling the complexities of WebRTC.
- [EJS](https://ejs.co/): A template engine for Node.js that allows for server-side rendering of HTML templates with JavaScript.
- [Passport.js](http://www.passportjs.org/): A flexible authentication middleware for Node.js that supports various authentication strategies, including Google authentication.

## Setup

1. Clone the project

```bash
   https://github.com/mallamsathwika/quickconnect.git
```

or download the zip file.

2. Go to the project directory and install dependencies

```bash
    npm install
```

3. Start the server

```bash
    nodemon server
```

4.Open the application in your web browser at `http://localhost:5000`
