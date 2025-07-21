Piotr Kostrzewa - CV Technical Overview
Technical Description of the CV Website
This repository hosts the source code for my personal CV website, built as a static HTML page with embedded CSS and external dependencies. Below is a technical breakdown:

File Structure:

CV_Piotr_Kostrzewa.html: The main HTML file containing the entire website structure and content.
piotr_kostrzewa.jpg: An image file used as a profile picture (to be uploaded separately).


Technologies Used:

HTML5: Structured with semantic tags and a responsive layout using a two-column grid (left sidebar and right content area).
CSS3: 
Custom styles defined in the <style> tag within the <head> section.
Utilizes W3.CSS (loaded from https://www.w3schools.com/w3css/4/w3.css) for pre-built responsive components and styling.
Google Fonts (Roboto, loaded from https://fonts.googleapis.com/css?family=Roboto) for typography.
Font Awesome (loaded from https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css) for icons.


JavaScript: No client-side JavaScript is implemented; the page is static.


Responsive Design:

Media query @media (max-width: 600px) adjusts the layout to a single-column view on smaller screens, ensuring mobile compatibility.
Animation fadeIn (1s duration) applied to .w3-card elements for a smooth loading effect.


Meta Tags:

<meta charset="UTF-8"> for character encoding.
<meta name="viewport" content="width=device-width, initial-scale=1"> for responsive scaling.
<meta name="description"> and <meta name="keywords"> for SEO optimization.


Navigation:

A fixed navigation bar (w3-bar w3-teal) with anchor links (#about, #experience, etc.) for smooth scrolling to sections.


Dependencies:

External CSS frameworks and libraries are loaded via CDN for ease of maintenance and updates.
No local dependencies or build tools required; the site is ready to host as-is.


Hosting:

Designed for static hosting on platforms like W3Schools Spaces (current deployment at https://piotrkostrzewa.w3spaces.com) or GitHub Pages.
File size is minimal, fitting within free hosting limits (e.g., 100 MB on W3Spaces).


Last Updated:July 21, 2025


This setup ensures a lightweight, accessible, and maintainable CV website. Contributions or suggestions for enhancements are welcome!
