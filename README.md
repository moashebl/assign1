README for My Website Project:
Overview
This project is a personal website created using HTML, CSS, and Bootstrap. The website includes a home page and a courses page that displays different sections. The goal was to design a responsive website that adapts to different screen sizes (desktop, tablet, and mobile).
How I Solved the Problem
1. Design and Structure:
o I first designed the website layout using the Bootstrap grid system to make it responsive.
o I structured the website with a navbar, jumbotron, and several content sections (home, courses, footer).
o For the layout of the courses page, I used columns to display different skills, and I ensured that the columns were responsive to adjust depending on the screen size.
o I added custom CSS to adjust padding, background, and footer positioning.
2. Responsive Layout:
o To ensure the page was responsive, I used the following Bootstrap grid classes:
 col-12 for extra small devices (taking up full width).
o The display: none; and display: block; CSS properties in JavaScript were used to switch between sections (Home and Courses) dynamically.
3. Footer at the Bottom:
o I ensured that the footer remained at the bottom of the page, even if the content didn't fill the entire screen. This was achieved using flex layout on the body and setting margin-top: auto on the footer.
4. Navbar:
o The navbar is sticky (fixed at the top), which ensures it is visible even when scrolling down the page.
o The collapse class ensures that the navbar is responsive and adapts well to smaller screens.
5. JavaScript:
o I used simple JavaScript to toggle between the "home" and "courses" sections. When a user clicks on a navbar item (Home or Courses), the corresponding section is displayed, and others are hidden.
Problems I Faced and How I Handled Them
1. Responsive Design Issues:
o Problem: Initially, some columns didn't adjust properly on smaller screens. This caused content to be misaligned or wrapped in a way that didn’t look good.
o Solution: I used Bootstrap’s responsive grid system (col-12) to ensure the layout would adjust to screen sizes. I also used custom CSS to add some space between columns and ensure proper alignment on different devices.
2. Footer Positioning:
o Problem: The footer would sometimes appear in the middle of the page or not at the bottom of the screen.
o Solution: I used flexbox in CSS to ensure the content area stretches and the footer is always at the bottom using margin-top: auto;.
3. Switching Between Sections:
o Problem: Initially, I had trouble with properly showing and hiding the sections (Home and Courses) when navigating through the navbar.
o Solution: I added a small JavaScript function that sets the display property of the sections based on the active one, ensuring that only the selected section is visible.
4. Image Size on Mobile:
o Problem: The profile image was not scaling correctly on smaller devices.
o Solution: I ensured the profile image scales according to the size of its parent container by adjusting its width using CSS and not relying on img-fluid.
