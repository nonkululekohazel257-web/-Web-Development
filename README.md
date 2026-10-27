 PART 1 /*HTML*/
1. Project Title:
Kids’ Fun Day – Game On... Let Play!

2. Student Information:
- Student Name: Nonkululeko Masinga
- Student Number: ST10491414
- Module: Web Development (Introduction)
- Assessment: Portfolio of Evidence (POE)

3. Project Overview:
Kids’ Fun Day is a community event website designed to promote outdoor activities, teamwork, healthy competition and physical fitness among children aged 9–11 in Ward 13, Kwa Novunula.
The website provides information about the event, games, team registration, winners, photographs and contact details. It aims to make event information accessible to children, parents, guardians, sponsors and volunteers.

4. Website Goals and Objectives:
- Promote the Kids’ Fun Day event.
- Allow participants to register online.
- Share event information, rules and schedules.
- Display event photographs and winners.
- Encourage sponsor and volunteer enquiries.
- Improve communication with parents and participants.

5. Key Features and Functionality:
- Home: Introduces the event and displays a dynamic greeting.
- About: Explains the organisation, mission and vision.
- Events and Games: Presents game information, rules and scoring.
- Registration: Provides a participant registration form.
- Gallery and Winners: Displays event photographs and winner information.
- Enquiry: Allows users to submit questions.
- Contact: Provides contact information and a contact form.
- JavaScript: Supports interactive features and form validation.
- CSS: Provides website styling and responsive design.

6. Technical Requirements:
- HTML for website structure.
- CSS for styling and layout.
- JavaScript for interactive functionality.
- Visual Studio Code for development.
- Git and GitHub for version control and project submission.

7. Timeline and Milestones:
1. Planning: Define the website purpose, target audience and objectives.
2. Design: Plan the website layout, navigation and colours.
3. Development: Create the HTML pages and CSS styling.
4. JavaScript: Add interactive features and form validation.
5. Testing: Check navigation, forms, links and page layout.
6. Part 1 Submission: Document the initial website and project requirements.
7. Future Updates: Improve and extend the website in later submissions.

8. Part 1 Details:
Part 1 covers the initial project planning and website development documentation, including the project overview, goals and objectives, proposed features, design, technical requirements and timeline.
Parts 2 and 3 will be added as required in future submissions.

9. Sitemap:
- Home
- About
- Events and Games
- Registration
- Gallery and Winners
- Enquiry
- Contact

10. Changelog:
- Created the initial website pages.
- Added website navigation and page content.
- Added CSS styling.
- Added JavaScript functionality where implemented.

Future Updates:
- Record new features, corrections and improvements here.
- Add the date and a short description for each update.

11. References:
- GoDaddy (2025). Website design reference. https://www.godaddy.com
- Yusufdemirci (2024). Success and teamwork concept with cartoon kids. Vecteezy. https://www.vecteezy.com


PART 2  /* CSS */
Project Name: Kids’ Fun Day – Game On... Let Play!

Project Overview:
A responsive website for a kids gaming event, built with HTML
Part 2 focuses on CSS improvements, responsiveness, and UI enhancements based on Part 1 feedback.

Update(new information pertinement)
- Unified 6 separate CSS files into one clean `style.css` to improve loading speed
- Fixed syntax errors: `border-radius: none` -> `12px`, `box-sizing: none` -> `border-box`
- Fixed missing class selectors: `kids-logo` -> `.kids-logo`
- Improved visual hierarchy with consistent purple theme (#7c3aed)
- Added responsive design for mobile (600px breakpoint)
- Added greeting banner with time-based JS greeting
- Optimized tables (.games-table, .budget-table) with hover effects and shadows
- Improved form accessibility with focus states

Changelog:
- NEW: Added greeting-banner component
- NEW: Added responsive media queries
- FIX: Removed duplicate body, header, nav, footer declarations (6x duplication)
- FIX: Corrected invalid CSS values (none values)
- FIX: Fixed form button transitions

  Initial:
- Created HTML pages: index, about, events, gallery, registration, contact
- Basic CSS styling for layout

References:
- Lecturer Feedback Document - Part 1
-image at https://www.magnific.com/vectors/kids-athletics.



/* java Script*/
 Updates:
- Implemented Error Handling: Changed from alert() only to inline DOM error messages with red borders and <small> error text for better UX
- Implemented AJAX Form Submission: Used fetch() API to submit contact, enquiry, and registration forms asynchronously without page reload.
- Improved validation: Email regex, 10-digit phone validation, loop validation for 10 participants
- Maintained responsive design and accessibility (aria-hidden, keyboard Escape to close lightbox)

Changelog:
- FEEDBACK EDITS from Part 2:
    - Fixed typo "purpule" in greetingBanner
    - Removed duplicate inline styles, now uses CSS class .greeting-banner
    - Added form reset after successful submission
- References updated

References:
- Deployed on Netlify:https://famous-capybara-ff9b0a.netlify.app/
- GitHub Repo: https://github.com/nonkululekohazel257-web/-Web-Development/edit/main/README.md










  
