:file_folder: [Public/](../)
# :open_file_folder: JS
Our folder containing all of the javascript for our front-end.
 ## :page_facing_up: login.js
The javascript for our login page. A user is given inputs to fill, then that information is sent to our router to communicate with the backend via an AJAX request. If they are successful, they should move on to the members portion of our application. Otherwise if there's an error, it's logged.
 ## :page_facing_up: member.js
This is the javascript that allows us to give our user a personalized greeting. On the page ready, an AJAX requests asks our database for a username associated with the account that was just logged in, and displays a "Welcome *user*" message.
 ## :page_facing_up: signup.js
Javascript that allows a user to create an account. Once the submit button is clicked, inputs are pulled off the input fields and an AJAX POST request is made to our controller/routes. If there's an error, a 500 server response is faded in on the screen.