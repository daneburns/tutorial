

<span style='color: crimson;'>

# CONFIGURATION

* :file_folder: [config/](.\Develop\config)
  * [middleware/](.\Develop\config\middleware)
    * [isAuthenticated.js](.\Develop\config\middleware\isAuthenticated.js)
  * [config.json](.\Develop\config\config.json)
  * [passport.js](.\Develop\config\passport.js)

</span>

<span style='color: teal;'>

# MODELS
* [models/](.\Develop\models)
  * [index.js](.\Develop\models\index.js)
  * [user.js](.\Develop\models\user.js)

<span style='color:salmon'>

# VIEWS

* [public/](.\Develop\public)
  * [js/](.\Develop\public\js)
    * [login.js](.\Develop\public\js\login.js)
    * [members.js](.\Develop\public\js\members.js)
    * [signup.js](.\Develop\public\js\signup.js)
  * [stylesheets/](.\Develop\public\stylesheets)
    * [style.css](.\Develop\public\stylesheets\style.css)
  * [login.html](.\Develop\public\login.html)
  * [members.html](.\Develop\public\members.html)
  * [signup.html](.\Develop\public\signup.html)


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
  