npm init
//Creates package.json file
npm install express socket.io moment
// installs express,socket.io and moment which is a dependency used to tell current time
npm install -D nodemon
//add script to package.json file as such to run next command
"scripts": {
    "start": "node server",
    "dev": "nodemon server"
  },
npm run dev
//Will start server and run it, this allows you to edit code
//while server is running with the server automatically restarting

https://www.youtube.com/watch?v=jD7FnbI76Hg
