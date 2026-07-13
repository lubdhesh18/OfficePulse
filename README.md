# OfficePulse – Personal Work Companion

![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![Status](https://img.shields.io/badge/status-Development-orange)
![License](https://img.shields.io/badge/license-MIT-green)
![Made With](https://img.shields.io/badge/Made%20With-JavaScript-yellow)

OfficePulse is a modern, lightweight, browser-based Personal Work Companion designed to help users efficiently manage office attendance, working hours, productivity insights, and daily work records.

Unlike traditional attendance trackers, OfficePulse focuses on providing an intuitive calendar-first experience with interactive dashboards, productivity summaries, and insightful visual reports.

The application runs entirely in the browser without requiring a backend server or database.


## ✨ Project Vision

OfficePulse aims to become an intelligent personal work companion that helps users:

- Track office attendance
- Monitor working hours
- Review historical records
- Visualize productivity trends
- Improve work discipline
- Maintain complete attendance history

Version 1.0 is intentionally designed as an offline-first application powered by Browser Local Storage while maintaining an architecture ready for future cloud synchronization.


# Features

## Attendance Management

- Calendar-first attendance tracking
- Daily Check-In / Check-Out
- Break duration management
- Working hour calculation
- Attendance editing
- Attendance deletion
- Notes for each workday


## Dashboard

- Daily working hours
- Weekly summaries
- Monthly summaries
- Average Check-In time
- Average Check-Out time
- Attendance percentage
- Present / Absent statistics


## Calendar

- Interactive monthly calendar
- Weekend highlighting
- Current date highlighting
- Selected date highlighting
- Attendance indicators
- Month navigation


## Reports

- Weekly reports
- Monthly reports
- Attendance distribution
- Productivity charts
- Working hour trends


## User Experience

- Modern responsive interface
- Smooth animations
- Light & Dark theme
- Toast notifications
- Empty state guidance
- User-friendly validation


# Technology Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Application Structure |
| CSS3 | Styling |
| Bootstrap 5 | Responsive Layout |
| JavaScript (ES6+) | Application Logic |
| Local Storage API | Data Persistence |
| Chart.js | Dashboard Charts |


# Project Structure

```
OfficePulse/

│
├── index.html
│
├── css/
│   ├── style.css
│   ├── variables.css
│   ├── animations.css
│   └── responsive.css
│
├── js/
│   ├── app.js
│   ├── storage.js
│   ├── calculator.js
│   ├── calendar.js
│   ├── ui.js
│   ├── charts.js
│   └── utilities.js
│
├── assets/
│   ├── images/
│   ├── icons/
│   └── fonts/
│
└── docs/
    ├── OfficePulse_SRS_v1.0.pdf
    └── OfficePulse_SDD_v1.0.pdf
```


# Application Architecture

```
User

↓

UI

↓

Application Controller (app.js)

↓

Storage
Calculator
Calendar

↓

Charts

↓

Dashboard
```

The application follows a modular architecture based on the Single Responsibility Principle (SRP), making it easy to maintain, test, and extend.


# Installation & Setup

## Clone the Repository

```bash
git clone https://github.com/lubdhesh18/OfficePulse.git
```

## Navigate into the Project

```bash
cd OfficePulse
```

## Open the Application

Simply open

```
index.html
```

inside any modern browser.

No installation required.

No database required.

No backend required.


# Development Roadmap

## Version 1.0

- Offline Attendance Tracking
- Interactive Calendar
- Dashboard
- Reports
- Local Storage
- Charts


## Future Versions

- Cloud Synchronization
- User Authentication
- Leave Management
- Team Dashboard
- Public Holiday Support
- Export to PDF / Excel
- Mobile Application
- REST API Integration


# Documentation

The project documentation is available inside the **docs/** directory.

- Software Requirements Specification (SRS)
- Software Design Document (SDD)

These documents define the functional requirements, software architecture, module design, algorithms, and implementation strategy of OfficePulse.


# Contributing

Contributions are welcome.

If you would like to contribute:

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature/your-feature
```

3. Commit your changes

```bash
git commit -m "Add your feature"
```

4. Push your branch

```bash
git push origin feature/your-feature
```

5. Open a Pull Request

Please ensure that:

- Code follows project structure
- Existing functionality remains unaffected
- New features include appropriate documentation


# Forking

You are welcome to fork this repository for learning, experimentation, or personal use.

If you build something inspired by OfficePulse, attribution is appreciated.


# License

This project is licensed under the MIT License.

See the [LICENSE](license) file for details.


# Author

**Lubdhesh18**

QA Engineer • DevOps Engineer

GitHub: https://github.com/lubdhesh18


# Acknowledgements

OfficePulse was designed following modern software engineering practices, including a comprehensive Software Requirement Specification (SRS) and Software Design Document (SDD) documentation before implementation.

The project emphasizes clean architecture, modular development, maintainability, and user-centered design.


### ⭐ If you find this project useful, consider giving it a star!

