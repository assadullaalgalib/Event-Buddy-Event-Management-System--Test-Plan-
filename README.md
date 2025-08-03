# Event-Buddy-Event-Management-System-Test-Plan

This repository contains the software quality and testing documentation for  
Event Buddy, a customized institutional event management system. The project was submitted for a Software Quality and Testing course at American International University-Bangladesh (AIUB).

---

## Project Overview

Event Buddy is designed to address the challenges of manually-managed events in academic settings, such as poor communication and decentralized planning. The system aims to streamline and automate the entire event lifecycle—from event creation and approval to registration and feedback—to improve efficiency and participant engagement.

---

## Core Features

Based on the provided Figma UI design, the system includes the following functional requirements:

- **User Login:** Allows users to log in using their email or username and password. A "Forgot Password" link is also available on the login screen.

- **User Registration:** New users can register with a form that includes fields for name, email, phone number, and password.

- **Homepage with Event List:** After logging in, users are redirected to a homepage that displays a list of upcoming events in a card-like format.

- **Event Details View:** Users can click on an event to view full details, including the title, date, time, and location.

- **Event Creation Form:** Provides a form for organizers to create new events with input fields for event title, date, time, description, and location.

- **Event Edit Form:** Organizers can edit existing events, allowing modifications to details like the title, date, and time.

---

## Testing Approach

The test plan ensures that all core functionalities visible in the interface are thoroughly tested through different levels of testing.

- **Testing Levels:** The project will undergo Unit Testing, Integration Testing, System Testing, and Acceptance Testing.

- **Test Tools:** Testing is primarily manual, supported by tools like Figma for UI validation, Browser Developer Tools, and Google Sheets/Excel for test case management.

- **Features Not to be Tested:** The test plan explicitly excludes several features based on the current UI design. These include the admin event approval panel, notification system, attendance check-in, password reset workflow, and user profile management.

---

## Project Details

- **Contributors:** MD ASSADULLA AL GALIB, MD ASIF CHOWDHURY, MEHERAF HASAN KHAN, and IMRAN HOSSAIN.

- **Institution:** American International University-Bangladesh (AIUB).

- **Programming Languages:** Next.js, NestJS.

- **UI Framework:** The system is designed using modern and scalable tools, though the document mentions both Flutter and Next.js for the front-end in different sections.

- **Database:** PostgreSQL.

- **Version Control:** Git will be used for version control, with the codebase hosted on GitHub for collaborative development.

