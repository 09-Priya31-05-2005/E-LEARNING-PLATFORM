# E-LEARNING-PLATFORM

*Company*: CODTECH IT SOLUTIONS

*Name*: N.Priyadarshini

*Intern Id*: CT08DF815

*Domain*: Front end webdevelopment

*Duration*: 8 weeks

*Mentor* : Neela Santosh

 The E-Learning Platform is a front-end web project created using HTML5, CSS3, and JavaScript. 
 
 It includes multiple pages such as the home page (index.html), a login page (login.html), a progress tracking page (progress.html), and a dynamic video viewing page (video.html).
 
 The goal of the platform is to provide a simple and clean interface that allows users to navigate through different sections, select courses, view course-related videos, and check their learning progress. No backend or database is involved; all functionalities are achieved on the client side using static files and scripting.

On the homepage (index.html), two main courses are listed: Web Development Bootcamp and Python Programming Essentials. Each course is displayed within a styled container that includes the course title, a brief description, level, duration, and a certification indicator. Each course also has a 'Start Learning' button that links to the video.html page with a URL parameter indicating the selected course (e.g., ?course=webdev or ?course=python). 

The page uses internal CSS to define styling for layout, buttons, navigation bars, and course cards. The navigation menu at the top allows users to move between the Home page, Progress page, and Video page easily.

The login page (login.html) features a user interface where users can input their email and password. It includes front-end validation to ensure that the email format is correct and that the password has a minimum length. Once the login form is successfully submitted, the user is redirected to the homepage (index.html). No server-side validation or authentication is used. 

JavaScript handles the form submission and performs simple input checks before redirection. The login interface is styled to be clean, centered on the page, and responsive for different screen sizes. The login page also includes placeholder links for "Forgot Password" and "Sign Up."

The progress page (progress.html) visually represents how much of each course a user has completed. It displays color-coded progress bars for each course with corresponding percentage values. The HTML structure uses styled divs to mimic progress bars, and the layout is designed to be easy to read and interpret. This is a static page, meaning the progress values are hardcoded for demonstration purposes. However, the structure allows for easy future integration with dynamic data once a backend is implemented. The overall theme and design of this page are consistent with the rest of the platform.

The video viewing functionality is centralized in a single page called video.html. This page dynamically loads different course videos based on the query parameter in the URL. 

JavaScript reads the parameter and updates the video iframe source, the course title, and the list of learning objectives accordingly. For example, when ?course=webdev is passed in the URL, the page loads a YouTube video for Web Development and displays the relevant course details. 

Similarly, if ?course=python is passed, it loads the Python course video and corresponding content. This dynamic behavior reduces redundancy and makes the code more scalable. The iframe is styled to be responsive and visually appealing.

Throughout the website, a consistent color scheme with blue highlights and white backgrounds is used. The design incorporates modern UI practices such as card layouts, shadows, padding, and rounded corners. Navigation bars are present on all pages except the login page and are implemented using simple anchor links. Each section is wrapped in containers for better structure and alignment. There is no external CSS or JavaScript file; all styles and scripts are embedded directly within the HTML files.

The platform includes no backend or user management. Everything from navigation to content rendering is handled on the front end. There is no persistent data storage; all information such as login status and course progress is simulated. This makes the platform ideal for static deployment or use as a front-end prototype for demonstration or academic purposes. The structure is modular, allowing for easy expansion by adding more courses, video links, or pages.

In conclusion, this E-Learning Platform project demonstrates the complete front-end development process for a multi-page educational site. It covers static content presentation, basic interactivity using JavaScript, dynamic content rendering via URL parameters, user input handling, and consistent design across pages. 

It does not include any database, server-side scripting, or authentication. However, it lays a solid foundation for future enhancements such as quizzes, certificates, dashboards, or backend integration. It effectively showcases a complete front-end implementation of an educational user interface using only HTML, CSS, and JavaScript.
