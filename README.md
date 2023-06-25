# React + MySQL

### Installing Node

1. Download the latest version of node from the [Node Downloads Page](https://nodejs.org/en/download). Download the version corresponding to your operating system; i.e. I am using a Mac, so I will download Node LTS for macOS. If a popup says that “this type of file may harm your computer” select “keep”.
2. Click on the installer and follow the instructions.
3. You should receive some form of confirmation message that you have installed node. To double check you have correctly installed node, go to your terminal and type “node -v” for the current node version. You should see a line with your current node version, in my case I see “v19.1.0”
4. Optional: If you think you may need to change versions of node in your project for any reason, you should install NVM (Node Version Manager). I won’t reinvent the wheel here, freeCodeCamp does a great job at this [here](https://www.freecodecamp.org/news/node-version-manager-nvm-install-guide/). 

### Installing React

1. Visit the [React documentation](https://react.dev/) for a full overview of React.
2. To install react globally, navigate in your terminal to where you want your app to be.
⋅⋅⋅ In my case, I went to where I store all my VSCode projects, made a new directory called “tutorials” and cd’d into this directory like so:

⋅⋅⋅ ````
    cd VSCode //Enter the VSCode directory/folder
    mkdir tutorials //Make tutorials directory
    cd tutorials //Enter tutorials directory
   ```
4. Use the command “npm install -g create-react-app”.

⋅⋅⋅ This will allow us to create a new react app from anywhere
5. To create our new react app, in the tutorials directory, I will use the command “npx create-react-app react_mysql_tutorial”

⋅⋅⋅This should both create a new react app, and install the basic react packages necessary for the project

### Creating A Backend Directory

1. While you are in your root directory for your app, in my case “react_mysql_tutorial”, and make a new folder called “frontend”.

⋅⋅⋅ We will place everything created from the create-react-app command in this directory
2. Create another folder under your project’s root directory called “backend”. 
3. In this directory, create a file called “server.js”

⋅⋅⋅ This will be where all of our server code will will go

### Creating a MySQL Database




