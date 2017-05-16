# Basic Static Server
A basic static server for serving up a static website, built on node and express.

Basic Static Server is exactly what it sounds like; a very basic server for serving up a static website. It's built on top of <a href="#">NodeJS</a> and utilizes the <a href="#">Express</a> framework. It's very simple to use, and very simple to build on top of.

It's Basic.

### How does it work?
Glad you asked.

First off, you need to make sure you have a couple of things installed on your machine.
* <a href="https://nodejs.org/en/" target="_blank">NodeJS</a>
* <a href="https://www.npmjs.com/" target="_blank">npm</a>

Then, once you have the repo cloned, open up your terminal and navigate to the appropriate directory, and install the dependencies.

    cd your-directory-name && npm install

Once all dependencies have been installed, you can start the server by running one of the following commands:

*// start the server on the default port (3000)*

    npm start
    
*// start the server on the specified port*
    
    npm start 4000

Navigate to localhost:PORT_NUMBER to see your site live!

### Folder Structure
Inside your directory you will find a folder called public. Inside this folder is where all of your site files will be placed.
    
    📂 your-directory-name
        📂 node_modules
        📂 public
            📂 assets
            📂 css
            📂 js
            index.html
        package.json
        server.js
        
**NOTE:** There must be an index.html file inside the root of the public folder in order for your site to be served properly from the root url (localhost:PORT_NUMBER). The rest is up to you.

### One more thing...
This is not yet optimized for a production environment, but I hope to have it at that state in the near future. It is advised to <strong>NOT</strong> use this as your production server without something like <a href="https://github.com/foreverjs/forever" target="_blank">Forever</a> built in.
