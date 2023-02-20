# CS465-fullstack
CS-465 Full Stack Development with MEAN
Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

The frontend developement customer side of the application was developed using Express node.js based framework. The handlebars to creat templates to render the HTML. The single page application (SPA) was developed using Angular. The SPA takes the first HTTPS request sent by the user to the site and retrieves the webpage and the functions. This provides the user with the fully finished page without having to constantly be connected to the network. This stops the page having to constantly connect and refresh the page. The downsides to using a SPA is that it takes longer to load on the first request. 

Why did the backend use a NoSQL MongoDB database?

The backend used NoSQL with MongoDB because it provides speed and stucture while maintaining functionality. MongoDB works well with JSON and JavaScript and a suitable use for MEAN applications. 

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JavaScript programming languages can be used for many applications. JSON is a type of data transmission format. The HTTP request contains the JSON data that the API requests to be processed by the compiler. JSON is used for the front end and when the user makes a HTTP request then the backend recieves and responds. 

Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

 Instances where we reused the user instances made sure we had fewer code to check for errors and makes the code easier to understand and replicate for other parts of the code. This keeps the code simple and makes it easier to understand the flow of data and how it can be reuesed for future parts.
 
 Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
 
 The code was tested using the console log for any error codes and doing live debugs of the server. We viewed any error codes and if the error code was poiting to missing directories. The log messages would tell us if there were any errors and where to find them in what class or server. We want to make sure the security endpoints were strong for the overall protection of the system. This application API method uses a POST and PUT request to check if the user is logged in before being able to edit any data. The method endpoint provides calls the database then the PUT issues and edit call then the POST issuse a create call then the GET issue read call the DELETE issue a delete call. 
 
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
 
The class has helped me reach my professional goals by teaching me how to build multiple types of web applications using MEAN. I developed a websit capable of using Express node.js and Single page applications using angular. I also learned how to use handle bars and the ability to utilize java for requests to a NoSQL databse. 
