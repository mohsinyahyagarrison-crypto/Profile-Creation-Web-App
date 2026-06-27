# Sky Blue Questionnaire System

A modern, fluid, and highly interactive multi-step questionnaire web application built with pure HTML, CSS, and JavaScript. The project features a seamless transition from a sliding Authentication Portal (Login/Registration) into a dynamic profile setup questionnaire with glassmorphic UI cards, micro-interactions, and state persistence.

##  Features

* **Elegant Authentication Portal (`index.html`):** A beautiful sky-blue and ocean-deep gradient layout with smooth sliding transitions between Login and Registration states.
* **Liquid Glow Transitions:** Custom transition effects that flash and fade elegantly when switching views or redirecting.
* **Multi-Step Questionnaire (`home.html`):** An intuitive step-by-step wizard capturing user details sequentially to avoid form fatigue.
* **Separated Education Track:** Dedicated individual steps for School, College, and University entries.
* **Progress tracking:** A real-time updating progress bar indicating how far the user is through the profile creation.
* **Smart UX Enhancements:** * Full "Back" button navigation support to edit previous steps.
  * Number-only validation for sensitive fields like Age.
  * Form state persistence using `localStorage` to prevent data loss on accidental page refreshes.
* **Interactive Profile Summary Review:** A final, scrollable verification screen where users can review all entered information before submission.

##  Tech Stack

* **Frontend:** HTML5, CSS3 (Flexbox, CSS Variables, Custom Keyframe Animations)
* **Scripting:** Vanilla JavaScript (ES6+)
* **Icons:** Font Awesome v6.4.0

##  File Structure

```text
├── index.html     # Auth Portal (Login / Registration & transition controller)
└── home.html      # Multi-step Questionnaire (Wizard, Validation, & Review Screen)
