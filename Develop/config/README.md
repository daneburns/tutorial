# :open_file_folder: Config * :file_folder: [middleware/](./Develop/config/middleware)
  This folder holds configuration files that manage user authentication, server setup and security.

  ## :page_facing_up: config.json
 Sets up 3 different server connections for the Sequelize package, a development, a test and a production database.

  ## :page_facing_up: passport.js
  A package for authenticating users. On submission of information (email, pw), passport checks this information to see if it exists and is accurate. The information is then stored in the database after being run through an encryption method and is retrieved the same way. This way information is never stored as a plain string.