# SELLEY-Backend---Node

This is backend for the react native expo project.
Click here for the:- [Front-end of the Project](https://github.com/himansh-gjr/SELLEY)

****

## Setup of the project

clone the repo `git clone https://github.com/himansh-gjr/SELLEY-Backend---Node`
change the directory in your local `cd SELLEY-Backend---Node` 

replace ip address to your ip address [config/development.json](https://github.com/himansh-gjr/SELLEY-Backend---Node/blob/main/config/development.json)

To install dependencies `npm i`

start the development server `node index.js`

**Please note* we are not using npm to start the project beacuse we are not using any database yet (you can go to the `store/` directory to see the implementation of the Store for our application, such as user, listings etc. ). NPM will cause to restart the server everytime we make a change to our files or we hit `cntrl + s` accidentally  and if we use NPM here we will lose our data once the server is restarted and we don't want that **

your development server will start on port `9000`
