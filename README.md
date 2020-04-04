

<span style='color: crimson;'>

# CONFIGURATION

* :file_folder: [config/](.\Develop\config)
  * :file_folder: [middleware/](.\Develop\config\middleware)
    * :page_facing_up: [isAuthenticated.js](.\Develop\config\middleware\isAuthenticated.js)
  * :page_facing_up: [config.json](.\Develop\config\config.json)
  * :page_facing_up: [passport.js](.\Develop\config\passport.js)

</span>

<span style='color: teal;'>

# MODELS
* :file_folder: [models/](.\Develop\models)
  * :page_facing_up: [index.js](.\Develop\models\index.js)
  * :page_facing_up: [user.js](.\Develop\models\user.js)

<span style='color:salmon'>

# VIEWS

* :file_folder: [public/](.\Develop\public)
  * :file_folder: [js/](.\Develop\public\js)
    * :page_facing_up: [login.js](.\Develop\public\js\login.js)
    * :page_facing_up: [members.js](.\Develop\public\js\members.js)
    * :page_facing_up: [signup.js](.\Develop\public\js\signup.js)
  * :file_folder: [stylesheets/](.\Develop\public\stylesheets)
    * :page_facing_up: [style.css](.\Develop\public\stylesheets\style.css)
  * :file_folder: [login.html](.\Develop\public\login.html)
  * :file_folder: [members.html](.\Develop\public\members.html)
  * :file_folder: [signup.html](.\Develop\public\signup.html)


</span>
<span style='color: lightblue;'>

# ROUTING AND CONTROLLERS
* [routes/](.\Develop\routes)
  * [api-routes.js](.\Develop\routes\api-routes.js)
  * [html-routes.js](.\Develop\routes\html-routes.js)
* [package.json](.\Develop\package.json)
* [server.js](.\Develop\server.js)
  
</span>

<span style='color: crimson;'>

## CONFIG FILES

</span>

* Config
  This folder holds configuration files that manage the 
** Middleware
 - isAuthenticated.js
Middleware for restricting certain routes that require a user to be logged in. If they try to send a request to any part of the application that requires an authenticated user, it redirects them to the login page.

- config.json 
  Sets up 3 different server connections for the Sequelize package, a development, a test and a production database.

- passport.js
  