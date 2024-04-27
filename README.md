# CS---465
CS-465 Full Stack development with MEAN

Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA). --
In my full stack project, I used a mix of HTML, JavaScript, and single-page applications to create a dynamic frontend. The core of the website was built with HTML and JavaScript, which not only gave the site its structure and style, but also managed its routes, controllers, and models. JavaScript was crucial for the main application file, where it helps export the Express application. The single-page application part focused on delivering admin functions, simplifying the process of managing and updating the website. For the views, I incorporated Express with handlebars and HTML to make the pages interactive and responsive.

Why did the backend use a NoSQL MongoDB database? -- 
The backend of our system was powered by a NoSQL MongoDB database, which we chose for storing specific pieces of information like trip details and user login data. One of the advantages of using MongoDB is its lack of a fixed schema, which makes it really convenient for users to add and change data as needed.

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces? --
The main difference between JSON and JavaScript is that JSON is designed primarily for storing data and doesn't support functions, which JavaScript objects can include. JavaScript objects are specific to JavaScript, but JSON is more flexible and can be used across different programming languages because of their similar structures. This makes it easy for JavaScript to convert JSON data. In practice, JSON is widely used to send data from the server's backend to the frontend of a website.

Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components. -- 
In this project, we improved functionality by making a couple of key changes in the code. First, we worked on the issue of duplicated HTML code by creating reusable components. Now, each page can dynamically call these components, making it easier and more efficient to load records from the database. Secondly, we streamlined the design by turning the header and footer into partials within Handlebars, allowing us to easily include them across various files for a consistent look and feel.

Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application. -- 
In this application, the API endpoints are essential for checking user credentials and granting them the authority to update database information. These endpoints work with various data methods like GET, POST, PUT, and DELETE to handle different actions. It’s crucial to secure these endpoints because without adequate security, unauthorized individuals could gain access to and potentially tamper with the data stored in the database.

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field? -- 
Taking this course has been a boost to my professional growth. Juggling a full-time job with school hasn't left much room for myself, but this class has really clarified what frontend and backend development are all about. Also, this course has really broadened my perspective on the career options available to me once I graduate in two months. The biggest takeaway for me has been learning how all the different pieces of code fit together to form a complete, functioning product. It's been enlightening to see how everything connects.
