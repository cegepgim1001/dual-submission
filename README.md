Faculty Grade Submission Hub

Overview

The Faculty Grade Submission Hub is an interactive, single-page web application designed to guide faculty members through the final grade submission process. It serves as a digital summary of faculty training, synthesizing key requirements, grading logic, and workflows into a user-friendly interface.

The application distinguishes between the two mandatory systems (Blackboard vs. Faculty Portal) and visually represents the official grading weights to ensure accuracy in transcript records.

Features

1. Interactive Dashboard

System Overview: Explains the "Dual-System Mandate," clarifying the specific roles of Blackboard (feedback) versus the Faculty Portal (official transcripts).

Visual Grading Weights: Utilizes Chart.js to render a dynamic Donut Chart representing the 40/30/30 split (Final Exam, Continuous Assessment, Midterm).

2. Step-by-Step Workflow

Interactive Stepper: A 6-step interactive guide that walks users through the submission process:

Log In

Navigate

Select Course

View Details

Enter Scores

Calculate

Detail View: Users click through steps to reveal detailed instructions, reducing cognitive load.

3. Critical Timeline

A visual timeline highlights key dates for the grading period, including submission deadlines and retake processing dates (e.g., February 4th).

4. Support & FAQ

Concerns Section: An accordion-style "Concerns & Discussion" panel addressing common faculty issues like duplicate work, large class sizes, and AI policies.

Resource Hub: Direct links to PDF guides, the Help Desk, and technical support contacts.

5. Video Integration

Includes a direct link to a local video resource (0001.mp4) titled "How to learn creation of web-sites from video for free!" opening in a new tab.

Technical Stack

HTML5: Semantic structure.

CSS Framework: Tailwind CSS (via CDN) for responsive styling and layout.

JavaScript Library: Chart.js (via CDN) for data visualization.

Fonts: Google Fonts (Inter) for typography.

JavaScript: Vanilla JS for DOM manipulation, state management (stepper logic), and event handling.

File Structure

The project relies on the following structure to function correctly:

/project-root
│
├── index.html            # Main application file
├── 0001.mp4             # Video tutorial file (referenced in the intro)
├── cyber_soho.png       # Logo image used in the footer
└── README.md            # Project documentation


Setup & Usage

Download: Ensure index.html, 0001.mp4, and cyber_soho.png are in the same local directory.

Run: Open index.html in any modern web browser (Chrome, Firefox, Edge, Safari).

Video Access: To view the linked video, ensure the 0001.mp4 file is present in the folder; otherwise, the link will result in a 404 error.

Customization

Color Palette

The design uses a "Warm Stone & Amber" palette to convey a minimalist, academic, and calm aesthetic:

Backgrounds: Stone-50 (#fafaf9), White

Accents: Amber-600 (#d97706)

Text: Stone-700 (#44403c)

Footer

The application includes a custom footer featuring the "Cyber Soho" branding and copyright notice.

Generated for the Faculty Grade Submission Hub.
