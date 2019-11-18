## About chat-app-30-client
This project was created using React.  It is an app where you can can host a chat app on your local server.

## Technologies used
* React
* React-Redux

## Installation
First run a local server by following the instructions detailed below:
Setting up the [server](https://github.com/AllanRaf/chat-app-server).

After setting up the server you can perform the following on your terminal.

Run the following (excluding the $ sign):
1. $ git clone https://github.com/AllanRaf/chat-app-client
2. Switch to the project directory
3. Find out your ip address by typing 
    * $ipconfig getifaddr en0
4. Set up an environment variable so that your local server is accessible to the outside world by typing:
    * export CHATAPP_SERVER_URL=<YOUR_IP_ADDRESS>/5000
    * <YOUR_IP_ADDRESS> will be the the one obtained by step 3.
3. $ npm install
4. $ npm start

The app runs on your local host (http://localhost:3000) in the browser.

Open your browser and type in http://localhost:3000.

5.  In the browser, create a new user account by supplying an email and password.
6.  Log in with the newly created account.
7.  You can now send messages that will be displayed in the browser window.
8.  Share your network address with a friend.  The address should be displayed after you type "npm start" in step 4 above and will be the same as <YOUR_IP_ADDRESS>/3000.

## Future improvements

* Improve the styling of the forms.
* Add a button to let a user log out.
* Add the ability to create new chat rooms.

