# College Club Management System

A lightweight front-end project for managing college clubs, students, and events in a single-page web application.

This project is designed as a simple dashboard where administrators can add club information, assign students to clubs, and track upcoming events and activities. The application stores data in the browser using `localStorage`, so records remain available when the page is refreshed without needing a backend or database.

## Project Overview

The system helps a college or club coordinator keep track of:

- Active clubs and their categories
- Club coordinators and descriptions
- Student members and their roll numbers
- Club memberships
- Event schedules, venues, and details

The interface includes separate sections for Clubs, Students, and Events, making the project easy to navigate and manage.

## Features

- Dashboard with summary statistics for clubs, students, and events
- Add, edit, and delete club records
- Add, edit, and delete student member records
- Add, edit, and delete event records
- Search records by name, category, description, email, venue, or club
- Automatic club dropdown population for student and event forms
- Validation for required fields and duplicate roll numbers
- Responsive layout for desktop and mobile screens
- Data persistence using browser `localStorage`

## Technologies Used

This project uses only browser-based front-end technologies present in the code:

- HTML5
- CSS3
- JavaScript
- Browser `localStorage` for data persistence

## Project Structure

- `index.html` — single-page application with layout, styles, and JavaScript logic
- `README.md` — project documentation

## How to Run

1. Open the project folder.
2. Double-click `index.html` to open it in your browser.
3. Use the navigation tabs to switch between Clubs, Students, and Events.
4. Add records, edit them as needed, and search through the lists.

Because this project is a static front-end application, there is no installation process or server setup required.

## Notes

- The application is designed as a prototype/demo for club management.
- All data is stored in the browser, so it is local to the machine and browser being used.
- Deleting a club also removes related students and events connected to that club.

## License

This project is provided for educational and demonstration purposes.
