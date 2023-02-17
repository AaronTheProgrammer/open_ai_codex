In this project, we build a chat bot AI that runs in the browser on http://localhost:5000 as long as both the server and client are running. 
You can type anything you want and engage in conversation with this bot. You can even ask this bot to write code in various programming languages
and frameworks! This bot uses the OpenAI API.

To build this project, first cd into the root directory of your project. Then, in the command line terminal, do this:

npm create vite@latest client --template vanilla

This creates the client folder.

Then, cd into the client folder and do this:

npm install

Now, the assets folder (which is within the client folder) and its contents must be added to the client folder manually by you.

Move favicon.ico from the assets folder to the public folder and delete vite.svg from the public folder.
Delete counter.js from the public folder as well.

Change main.js (in public) to script.js


You will need to create the server folder yourself and put it in the root directory of the project.
Open up another terminal and cd into the server folder. Do this:

npm init -y
npm install cors dotenv express nodemon openai


To run the server, use npm run server in one command line terminal. Then, to run the client, go into another command line terminal and run npm run dev. 
On both terminals you must be in the proper directory (the server directory and the client directory respectively).


