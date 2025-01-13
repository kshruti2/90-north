Responsive Webpage

Overview

This project is a responsive webpage designed with a fixed navbar, a three-section layout below the navbar (left menu, main content area, right panel), and a footer. The layout adapts to different screen sizes using JavaScript and CSS.

Features

Fixed Navbar: The navbar remains visible at the top while scrolling.

Three-Section Layout:

Left Menu: Collapsible menu on the left.

Main Content Area: Centered section for primary content.

Right Panel: Panel on the right side for additional content.

Footer: Fixed at the bottom of the page.

Responsive Design: The page adjusts its scale based on screen width for better usability.

Scaling Rules

992px to 1600px: Page shrinks to 90%.

700px to 767px: Page shrinks to 80%.

600px to 700px: Page shrinks to 75%.

600px or below: Page shrinks to 50%.

File Structure

project-folder/
├── index.html    # Main HTML file
├── README.md     # Documentation

How to Use

Clone the repository:

git clone <repository_url>

Open index.html in a web browser to view the webpage.

Resize the browser window to see the responsive behavior.

JavaScript Functions

toggleMenu()

Toggles the visibility of the left menu by adding or removing the collapsed class.

adjustPageSize()

Adjusts the page scaling based on the screen width using the following logic:

Calculates the scale factor.

Applies the scale to the entire page using CSS transform.

Browser Compatibility

Tested on:

Google Chrome

Mozilla Firefox

Microsoft Edge

License
