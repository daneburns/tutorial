### :open_file_folder: [root/](https://github.com/daneburns/tutorial/)
# :open_file_folder: Routes
This folder holds our routes and controller files that manages the relationship between our models and views.

  ## :page_facing_up: api-routes.js
This file contains all the routes for our back-end and models. 
 * /api/login 
   * handles the route request for the url. This is where we check our user via passport to ensure that the information being sent over via the POST route has a value in our database.
 * api/signup
   * handles the route request for the above url. This is where we create a User model that we have defined in the models folder, under user.js. If there is an error a 401 server status code is sent. Otherwise, the user is redirected to the login page detailed above.
* api/logout
  * handles the logout functionality. 
* api/user_date
  * This route is responsible for pulling down data associated with the user. Currently it is used to send a personalized greeting message. On success, it sends back the user information. Not great for security! 

  ## :page_facing_up: html-routes.js
  This file contains all the routes for delivering our html requests (navigation).
  * /
    * This route will send a user to the members-only page with out personalized greeting if they are already signed in. Otherwise, it redirects them to a signup page.
  * /login
    * This route checks to see if the user is signed in, otherwise it sends them to a login page.
  * /members
    * This route accesses the middleware we've included and checks to see if the user is authenticated (logged in).