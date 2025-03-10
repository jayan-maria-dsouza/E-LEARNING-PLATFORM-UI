# E-LEARNING-PLATFORM-UI

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: JAYAN MARIA DSOUZA

*INTERN ID*: CT08TKG

*DOMAIN*: FRONT END DEVELOPMENT

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

# Description

This code represents a foundational structure for an e-learning platform, built using HTML, CSS, and JavaScript, and developed within the Visual Studio Code environment for cross-browser compatibility. The platform is designed to offer courses in various programming and computer science topics, providing users with access to learning materials and a dashboard to track their progress.

The HTML structure consists of three core pages: index4.html (Home), course.html (Courses), and dashboard.html (Dashboard). Each page shares a common header with a navigation bar that allows users to switch between these pages. The navigation bar, contained within the <nav> element, provides links to "Home," "Courses," and "Dashboard," ensuring easy navigation.

The index4.html and course.html pages display a list of courses in a grid layout, using the <section id="course-list"> element. Each course is presented in a div with the class "course-card," which includes an image, a course title, and a "Watch" button. The "Watch" button links to external resources, simulating access to the course content. The images are sourced from local paths, which would need to be replaced with actual web-accessible URLs for a deployed application. The course.html page essentially duplicates the course listing from index4.html, indicating a potential design redundancy that could be streamlined in a more refined version.

The dashboard.html page provides a basic course progress tracking feature. It uses JavaScript to dynamically generate a list of tracked courses and their progress, which is stored in the browser's localStorage. The progress is represented as a percentage of a hypothetical 3600-second (1-hour) video, allowing users to visualize their learning journey. This page demonstrates the use of client-side storage and dynamic content generation, essential for creating interactive web applications.

The CSS styles, located in style4.css, provide a clean and consistent visual design across the platform. The body of the page is set with a light gray background and a sans-serif font, creating a readable and professional appearance. The header is styled with a royal blue background, white text, and a flexible layout to accommodate the navigation bar and potential additional elements. The navigation bar is centered and styled with white links, ensuring clear visibility against the blue background.

The course cards are designed with a white background, rounded corners, and a subtle box shadow, providing a visually appealing presentation. The "Watch" buttons are styled with a royal blue background and white text, matching the header's color scheme. The dashboard page utilizes a white background for the progress list, enhancing readability. The footer, styled with a dark background and white text, is positioned at the bottom of the viewport, providing a consistent footer across all pages.

The JavaScript code in dashboard.html demonstrates basic client-side functionality, using localStorage to store and retrieve course progress. The DOMContentLoaded event listener ensures that the script runs after the DOM is fully loaded. The script iterates through a predefined list of courses, retrieves their progress from localStorage, and dynamically generates HTML elements to display the progress. This approach allows users to track their progress locally, without requiring a server-side database.

The implementation, developed within Visual Studio Code, adheres to standard web technologies (HTML, CSS, JavaScript), ensuring compatibility across modern browsers. The use of relative units and flexible layouts contributes to a responsive design, adapting to different screen sizes. The code is structured to facilitate further development, allowing for the addition of more features and content. The platform's foundation, while basic, provides a solid starting point for a more comprehensive e-learning system.

# OUT PUT

![Image](https://github.com/user-attachments/assets/f4a30728-3b08-405b-b087-857dadf390d4)

![Image](https://github.com/user-attachments/assets/1bf7c72f-0e2d-4044-874f-d4205255470a)

![Image](https://github.com/user-attachments/assets/4f2e6b3b-8756-4f63-a0ac-60a1ae0e8466)
