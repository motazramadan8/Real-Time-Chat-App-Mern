# Snappy - Chat Application 
Snappy is a chat application build with the power of MERN Stack & Socket Io


![login page](./images/snappy_login.png)

![home page](./images/snappy.png)

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)
- [Express](https://expressjs.com/)
- [Socket Io](https://socket.io/)

Both should be installed and make sure Mongodb is running.

``` shell
git clone [https://github.com/koolkishan/chat-app-react-nodejs](https://github.com/motazramadan8/Real-Time-Chat-App-Mern.git)
cd Real-Time-Chat-App-Mern
```
Now rename env files from .env.example to .env
``` shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.
