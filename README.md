#GitHub Repo Link - https://github.com/adityasoam55/Student-registration

Student Registration System
Overview
The Student Registration System is a web-based application that allows users to manage student records. It provides functionality to add, edit, and delete student details, including name, class, address, email, and contact number. The data is stored persistently in the browser's localStorage, ensuring that records are retained across page reloads.
Features

Add Students: Register new students with their details.
Edit Students: Update existing student records.
Delete Students: Remove student records with a confirmation prompt.
Data Persistence: Student data is saved in localStorage for persistence.
Responsive Design: Built with Tailwind CSS for a clean, mobile-friendly UI.
Scrollable Table: Displays registered students in a table with a vertical scrollbar for large datasets.

Technologies Used

HTML: Structure of the web application.
CSS (Tailwind CSS): Styling for a modern and responsive UI.
JavaScript: Handles form submission, table rendering, and local storage operations.
LocalStorage: Browser-based storage for persistent data.

Getting Started
Prerequisites

A modern web browser (e.g., Chrome, Firefox, Edge).
No additional software or dependencies are required, as the project uses a CDN for Tailwind CSS.

Installation

Clone or download the project repository to your local machine.
Open the index.html file in a web browser to run the application.

Usage

Add a Student:
Fill out the form with the student's name, class, address, email, and contact number.
Click the "Register Student" button to add the student to the table.


Edit a Student:
Click the "Edit" button next to a student's record in the table.
Update the form fields and click "Update Student" to save changes.
Click "Cancel" to discard changes.


Delete a Student:
Click the "Delete" button next to a student's record.
Confirm the deletion in the prompt to remove the student.


View Students:
The table displays all registered students, with a scrollbar for large lists.
Data persists across page reloads via localStorage.



File Structure
├── index.html        # Main HTML file containing the UI and JavaScript logic
└── README.md         # Project documentation

