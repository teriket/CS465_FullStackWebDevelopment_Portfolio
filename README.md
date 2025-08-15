# CS465_FullStackWebDevelopment_Portfolio

This was a full stack web application designed for the company Travlr Getaways, who wanted to modernize their platform.  The website runs a RESTful API using a MEAN stack.

## Architecture
  Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
  
Express HTML was fast to develop a usable interface and creates static HTML that search engines use for SEO.  The downside is that Express HTML would be difficult to modify in the long term.  Javascript allowed me to create HTML elements with dynamic content from a database, but was more complex to implement than Express HTML.  Angular components allowed me to create a single paged application with dynamic components that can easily be reused, but had the greatest complexity to implement.

  Why did the backend use a NoSQL MongoDB database?
  
MongoDB was appropriate for the website for a few reasons.  The variety of services from the website benefits from a flexible document schema over creating multiple, rigid tables in a relational database.  MongoDB also scales horizontally, which is more cost effective to scale with.

## Functionality
  How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
  
While javascript is a turing complete programming language (pretending infinite memory exists), JSON is a method of storing data in key: value pairs.  This makes JSON a good tool to pass information between the front and back end.  For example, user information is passed in the form of JSON from the server to the client, which is then parsed by javascript.

  Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
  
I refactored code to escalate the complexity of the project.  It is often easier to build the application piecemeal rather than with it's final architecture.  For example, much of the code was initially built with static HTML.  This made it easier to build dynamic webpages using javascript and handlebars.  This culminated in building reusable components in Angular.  The benefits of creating reusable components is that changes are made globally to components, reducing the risk of errors.

## Testing

  Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.
  
Methods, endpoints, and security are necessary for passing data between a user and the servers.  Methods abstract away the implementation of specific piece of functionality, and make the function reusable elsewhere.  Endpoints enable URI requests to return data from the backend to the front end.  Securing the API is both a legal and ethical responsibility of the developer.  In the context of the full stack application, security is about who is allowed to do what with the API, such as posting new reviews, adding HTML to the website, and viewing account details.

## Reflection

  How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?
  
This course has helped me to integrate core computer science skills (data structures, security, usability, algorithms, etc.) into a singular project.  It has also helped me understand and make software architectural decisions.  It has also gotten my feet wet working over the internet, which is a skill most software engineers must have.
