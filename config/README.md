### :open_file_folder: [root/](../)
# :open_file_folder: Config
This folder holds configuration files that manage user authentication, server setup and security.
 > :file_folder: [middleware/](./middleware)
  

  ## :page_facing_up: config.json
 Sets up 3 different server connections for the Sequelize package, a development, a test and a production database.

  ## :page_facing_up: passport.js
  A package for authenticating users. On submission of information (email, pw), passport checks this information to see if it exists and is accurate.