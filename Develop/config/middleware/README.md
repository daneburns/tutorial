:file_folder: [config/](../config)
# :open_file_folder: Middleware
Our folder containing all of the middleware.
 ## isAuthenticated.js
Middleware for restricting certain routes that require a user to be logged in. If they try to send a request to any part of the application that requires an authenticated user, it redirects them to the login page.