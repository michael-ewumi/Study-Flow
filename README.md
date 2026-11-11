StudyFlow — Academic Planner

StudyFlow is a lightweight, interactive academic planner designed to help students organize coursework, manage priorities, track deadlines, and monitor their weekly progress.

The application runs entirely in the browser, with tasks validated and stored locally using the browser's localStorage. No account, backend server, or database is required.

Features

Add academic tasks

Assign courses to tasks

Set due dates

Set task priorities

Mark tasks as completed

Filter tasks by:

All

Active

Completed

Sort tasks by:

Due date

Priority

Newest

Track total, completed, and active tasks

View weekly completion progress

Clear completed tasks

Reset sample tasks

Automatically save tasks locally

Dark/light theme support

Responsive interface

Accessible form validation and status feedback

How It Works

StudyFlow uses browser-based storage to save tasks locally.

User
  ↓
Add / Edit / Complete Task
  ↓
JavaScript Validation
  ↓
Task State
  ↓
localStorage
  ↓
Task List + Statistics

Because the data is stored in localStorage, tasks remain available after refreshing the page but are specific to the browser and device being used.

Technologies

HTML5

CSS3

Vanilla JavaScript

Browser localStorage API

Google Fonts

No frontend framework or build system is required.

Project Structure

StudyFlow/
├── index.html
├── planner.html
├── css/
│   └── styles.css
├── js/
│   ├── main.js
│   └── planner.js
├── assets/
│   └── img/
└── README.md

The exact structure may vary depending on the files included in the repository.

Getting Started

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/StudyFlow.git

2. Open the project

Open the project folder in VS Code or another code editor.

3. Run the application

Because StudyFlow does not require a build step, you can open the HTML file directly in a browser.

For development, you can also use the Live Server extension in VS Code.

Data & Privacy

StudyFlow is designed to keep planner data local.

Tasks are stored using the browser's localStorage API. The planner does not require an account or send task data to a remote server.

This means:

No account is required

No database is used

Tasks remain on the current browser/device

Clearing browser data can remove saved tasks

Tasks do not automatically appear on another device or browser

Validation

The planner validates task information before adding it to the task list.

For example, the task title is required and due dates cannot be set in the past.

Validation feedback is displayed directly within the interface to help users correct input errors.

Accessibility

StudyFlow includes accessibility-focused features such as:

Semantic HTML

Form labels

Keyboard navigation

Skip navigation link

ARIA labels and live regions

Screen-reader-friendly status messages

Accessible task controls

Focus management during validation

Design

The interface was designed around a clean academic productivity experience, with an emphasis on:

Clear information hierarchy

Minimal distractions

Responsive layouts

Readable typography

Progress visibility

Simple task management

Future Improvements

Possible future improvements include:

Task editing

Recurring tasks

Calendar integration

Export/import of tasks

Cloud synchronization

User accounts

Cross-device synchronization

Notifications and reminders

Academic semester management

Course-specific analytics

Project Purpose

StudyFlow was created as a practical web development project demonstrating the use of HTML, CSS, JavaScript, browser APIs, form validation, DOM manipulation, state management, and responsive interface design.

It is also part of my broader academic and professional portfolio as a Cybersecurity student interested in secure web development and practical software projects.

Author

Michael Ewumi

Cybersecurity Student
Miva Open University

GitHub: github.com/michael-ewumi

License

This project is available for educational and portfolio purposes.

If you would like to reuse or modify the project, please provide appropriate attribution.
