# Chat Application
**Group:** SE-2211 <br />
**Creators:** Yernur Koishybayev, Alinur Alipov, Alikhan Dosmaganbetov

## Application Description
Realtime chat app with websockets using Node.js, Express and Socket.io with Vanilla JS on the frontend. The purpose of this code is to create a chat application on a local server. Thanks to it, you can enter pre-created teams and participate in a discussion on a particular topic.

## Usage 
```
npm init
npm install express socket.io moment
npm install -D nodemon 
```

## Installation and Launch
1. Download files from the repository
2. In the terminal, write the lines indicated above in the Usage block
3. In the `package.json` file, replace the script written on line 7 with the following lines:
   ```
    start": "node server.js",
    "dev": "nodemon server.js"
   ```
4. Write `npm run dev` into the terminal
5. Go to localhost:3000 in the browser
