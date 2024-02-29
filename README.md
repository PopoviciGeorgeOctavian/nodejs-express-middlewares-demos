Game name Generator using Body Parser

    File: index1.js
    Description: A simple web server that takes user input from a form, uses body-parser middleware to parse the incoming request body, and displays a response acknowledging the submission.

Logging with Morgan

    File: index2.js
    Description: Illustrates the use of the Morgan middleware for logging HTTP requests in a concise format.

Request Logger Middleware

    File: index3.js
    Description: Implements a custom middleware to log request method and URL before processing the route.

Game Name Generator using Custom Middleware

    File: index4.js
    Description: A web server that generates an in-game name based on user input and displays it on form submission.

Password-Protected Web Page

    File: index5.js
    Description: Demonstrates a simple Node.js application using Express to create a password-protected web page. The server checks the provided password against a predefined value using the body-parser middleware and           grants access accordingly.


Tools Used

    Express.js: A web application framework for Node.js.
    Body Parser: Middleware to parse incoming request bodies.
    Morgan: HTTP request logger middleware for Node.js.
    Nodemon: A utility that monitors for changes and automatically restarts the server. 

Usage
Running with Nodemon

     Runned each example using nodemon for automatic server restarts, execute the respective file with the following command:
     bash: nodemon index1.js or index4.js..  etc

Testing with Postman

    Used the Postman app to test the web server's functionality. Make HTTP requests to the provided endpoints (e.g., /submit) and observe the server's responses.
