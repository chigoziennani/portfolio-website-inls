Chigozie's Portfolio Website
This is a multi-level personal portfolio website built for school. The site demonstrates hard coding skills using HTML, CSS, JavaScript, and a simple PHP server-side script. The design is inspired by a dark, cinematic "Movie Palace" aesthetic, and the site meets various navigation, styling, and accessibility requirements.

Project Structure
bash
Copy
Edit
/your-project-folder
├── index.html                # Home page with global navigation and dynamic JS features
├── about.html                # About Me page with an image, contact form, and server-side integration
├── courses.html              # Courses page listing current courses with bullet points
├── interests.html            # Interests page featuring a list of 10 books and third-level navigation
├── resume.pdf                # Downloadable résumé
├── styles.css                # Shared CSS file for the entire website
├── scripts
│   └── server-script.php     # Server-side PHP script for processing form submissions
└── interests                 # Folder for third-level pages related to Interests
    ├── books.html            # Books page (third-level under Interests)
    ├── hobbies.html          # Hobbies page (third-level under Interests)
    └── travel.html           # Travel page (third-level under Interests)
Features
Responsive & Consistent Design:
All pages share a dark, cinematic aesthetic with a consistent color scheme, typography, and layout.

Navigation:

Global fixed header with links to Home, About, Courses, and Interests.
Each page includes links to other sections to ensure easy navigation.
Third-level pages under Interests (Books, Hobbies, Travel) include explicit secondary navigation back to the Interests page and among sibling pages.
Dynamic Functionality:

A JavaScript snippet (located at the bottom of index.html) dynamically sets the "Last updated" date in the footer.
The contact email is dynamically assembled in JavaScript to protect it from harvesters.
Server-Side Script:

A PHP script (scripts/server-script.php) processes form submissions from the About page contact form. This demonstrates a simple integration of server-side functionality.
Image Usage:

The About page includes a proportionally scaled headshot image (chi_headshot.jpg) with styling enhancements.
How to Run
Download/Clone the Repository:
Ensure you have all files and folders as described in the project structure.

Local Server:
Since the project includes a PHP script, run the project using a local server (such as XAMPP, MAMP, or using the built-in PHP server):

bash
Copy
Edit
php -S localhost:8000
Then navigate to http://localhost:8000/index.html in your browser.

Contact Form Testing:
On the About page, fill out the contact form and submit to test the PHP script. The server-side script will process your submission.

Instructor Notes
JavaScript Code:
The JavaScript code that dynamically sets the "Last updated" date and assembles the contact email can be found at the bottom of index.html (just before the closing </body> tag).

Server-Side Script:
The server-side functionality is implemented in the file scripts/server-script.php, which processes form submissions from the contact form on the About page.

Credits
Design Inspiration:
The site design is inspired by the "Movie Palace" aesthetic, featuring a dark background, accent colors (red and gold), and smooth hover transitions.

Built by:
Chigozie Nnani