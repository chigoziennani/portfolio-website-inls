# Portfolio Website for Chigozie Nnani

This repository contains all the files for my portfolio website, built as part of my school project for the **Tools for Information Literacy** course at UNC Chapel Hill. This project demonstrates my skills in HTML, CSS, JavaScript, and PHP, and includes multi-level navigation, dynamic content, and a dark, cinematic design inspired by the "Movie Palace" aesthetic.

## Project Overview

**Goal**: Build a multi-level personal website  
**Technologies/Techniques In Focus**: HTML, CSS, JavaScript, PHP (server-side), Responsive Design, Dynamic Navigation, Email Obfuscation  

**Description**:  
This project features a portfolio website that includes:  
- A **Home** page with a grid-based layout and dynamic JavaScript elements.
- An **About Me** page that includes a proportionally scaled headshot, a detailed description, a downloadable résumé, and a contact form that submits data to a PHP script.
- A **Courses** page listing current courses with bullet-point lists.
- An **Interests** section with third-level pages (**Books**, **Hobbies**, **Travel**) that include explicit secondary navigation back to the main Interests page and links among the third-level pages.

## Key Features

- **Responsive & Consistent Design:**  
  The site utilizes a dark, cinematic theme with a unified color scheme, typography, and layout across all pages.

- **Dynamic JavaScript:**  
  A JavaScript snippet (located at the bottom of `index.html`) dynamically sets the "Last updated" date and assembles the contact email from separate variables to protect it from harvesters.

- **Server-Side Processing:**  
  A PHP script (`scripts/server-script.php`) processes contact form submissions on the About page.

- **Multi-Level Navigation:**  
  Global navigation is available on every page. The Interests page includes secondary navigation linking to all third-level pages (Books, Hobbies, Travel) and back to the main Interests section.

## How to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/chigoziennani/portfolio-website-inls.git
2. **Open in Your Preferred Editor:** Navigate to the project folder and open it in Visual Studio Code or any editor of your choice.
3. **Run a Local Server:** Since the project includes a PHP script, start a local server (e.g., using XAMPP, MAMP, or PHP’s built-in server):

    ```bash
    php -S localhost:8000
    ```
    Then open your browser and go to http://localhost:8000/index.html.

## Credits
**Built by:** Chigozie Nnani

**Design Inspiration:** A dark, cinematic "Movie Palace" aesthetic with a focus on clean navigation and dynamic interactivity.
