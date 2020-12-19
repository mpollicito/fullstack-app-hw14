This application is made up of files and folders, below you will find a layout and description of this app's components:

root folder/directory of app
    server.js is what brings everything together
        contains required components and logic for webpage
    
    package.json contains the node dependencies
    
    License chosen is MIT, the README file contains information specific to the app

    config folder
        config and passport files
            config file is JSON and contains info needed to communicate with server
                passport.js contains logic for login page and its' information

        middleware
            isAuthenticated file determines if user is logged in 

    models folder
        contains javascript files which can create and interact with a database

            
    package.json
        contains all dependencies for what is required by this app

    public folder
        HTML pages for front end code which communicates to back-end
        
        js folder
                Contains javascript files with the logic for each HTML page counterpart
        stylesheets
            Style css file for html here

    routes folder
        This folder contains javascript files
            Requests and routing for webpage here, both HTML and API

---