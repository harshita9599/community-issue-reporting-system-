# Community Issue Reporting System

A Flask-based web application that enables citizens to report community issues directly to local authorities through a centralized complaint management platform.

The system simplifies issue reporting, complaint tracking, authority management, and citizen feedback while promoting transparency between citizens and government authorities.

---

## Project Overview

Community Issue Reporting System is a role-based web application developed to streamline communication between citizens and local authorities.

Citizens can report civic issues such as water leakage, sanitation problems, road damage, electricity failures, and other public infrastructure concerns. Authorities can review complaints, update issue status, provide official comments, and notify citizens about progress until the issue is resolved.

The platform provides complete transparency by allowing users to monitor complaint progress and confirm successful resolution.

---

## Features

### Citizen Module

- User Registration & Login
- Report Community Issues
- Upload Images
- View Complaint History
- Track Complaint Status
- View Authority Comments
- Submit Feedback
- Confirm Issue Resolution

### Authority Module

- Secure Authority Login
- State-wise Complaint Management
- Dashboard Statistics
- Update Complaint Status
- Add Resolution Comments
- View Pending Issues
- View Issues In Progress
- Manage Resolved Complaints

### General Features

- Role-Based Authentication
- Complaint Tracking
- Category Filtering
- State Filtering
- SQLite Database
- Responsive UI
- Image Upload Support
- Feedback System

---

## Technology Stack

### Frontend

- HTML5
- CSS3
- JavaScript
- Bootstrap

### Backend

- Python
- Flask

### Database

- SQLite

### Libraries

- Jinja2
- Werkzeug

---

## System Workflow

Citizen Login

↓

Report Issue

↓

Issue Stored in Database

↓

Authority Reviews Complaint

↓

Status Updated

↓

Authority Adds Comment

↓

Citizen Tracks Progress

↓

Citizen Gives Feedback

↓

Citizen Confirms Resolution

↓

Issue Closed

---

## Screenshots

Complete application screenshots are available inside the **screenshots** folder.

The screenshots demonstrate:

- Homepage
- Login
- User Dashboard
- Report Issue
- Complaint Tracking
- Authority Dashboard
- Resolution Management

---

## Documentation

Detailed documentation is available inside the **docs** folder.

Included documents:

- System Architecture
- Database Design
- Project Workflow
- Implementation Details
- Final Project Report

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Community-Issue-Reporting-System.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run

```bash
python app.py
```

Visit

```
http://127.0.0.1:5000
```

---

## Future Enhancements

- Email Notifications
- Google Maps Integration
- Real-time Notifications
- Mobile Application
- AI-based Complaint Classification
- Analytics Dashboard
- Cloud Deployment

---

## License

This project was developed for academic and educational purposes.
