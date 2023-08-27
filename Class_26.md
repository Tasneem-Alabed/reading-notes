# MVC
is a design pattern or architecture which helps in developing the web application in a most efficient way when compared with the traditional ASP.NET Web Application.
In MVC the View only deals with UI of the page and the user actions are defined in Controller. MVC is action-based architecture. Based on the action, an appropriate View is displayed. The organization of the code inside MVC is very clean and organized
In MVC, we don’t have View State to store the state information. In MVC, we don’t have the concept of page life cycle. When a request is made, the request hits the Controller which, in turn, hits the appropriate action. Then, the controller collects the required data from model and it is rendered in the appropriate View to user. So the response time is very low.
MVC makes the design of the application into three layers namely Model, View, and Controller. Each of these components are built to handle different aspects of the application.

# Tag Helpers in ASP.NET Core
Tag Helpers enable server-side code to participate in creating and rendering HTML elements in Razor files. For example, the built-in ImageTagHelper can append a version number to the image name. Whenever the image changes, the server generates a new unique version for the image, so clients are guaranteed to get the current image (instead of a stale cached image).
For the most part, Razor markup using Tag Helpers looks like standard HTML. Front-end designers conversant with HTML/CSS/JavaScript can edit Razor without learning C# Razor syntax.


