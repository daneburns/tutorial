

<span style='color: crimson;'>

# CONFIGURATION

* :file_folder: [config/](./config)
  * :file_folder: [middleware/](./config/middleware)
    * :page_facing_up: [isAuthenticated.js](./config/middleware/isAuthenticated.js)
  * :page_facing_up: [config.json](./config/config.json)
  * :page_facing_up: [passport.js](./config/passport.js)

</span>

<span style='color: teal;'>

# MODELS
* :file_folder: [models/](./models)
  * :page_facing_up: [index.js](./models/index.js)
  * :page_facing_up: [user.js](./models/user.js)

<span style='color:salmon'>

# VIEWS

* :file_folder: [public/](./public)
  * :file_folder: [js/](./public/js)
    * :page_facing_up: [login.js](./public/js/login.js)
    * :page_facing_up: [members.js](./public/js/members.js)
    * :page_facing_up: [signup.js](./public/js/signup.js)
  * :file_folder: [stylesheets/](./public/stylesheets)
    * :page_facing_up: [style.css](./public/stylesheets/style.css)
  * :file_folder: [login.html](./public/login.html)
  * :file_folder: [members.html](./public/members.html)
  * :file_folder: [signup.html](./public/signup.html)


</span>
<span style='color: lightblue;'>

# CONTROLLERS
* :file_folder: [routes/](./routes)
  * :page_facing_up: [api-routes.js](./routes/api-routes.js)
  * :page_facing_up: [html-routes.js](./routes/html-routes.js)
* :page_facing_up: [package.json](./package.json)
* :page_facing_up: [server.js](./server.js)
  
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
  