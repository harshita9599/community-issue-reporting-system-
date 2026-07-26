# 📸 Project Screenshots

This folder contains screenshots demonstrating the complete workflow of the **Community Issue Reporting System**, a Flask-based web application designed to bridge the communication gap between citizens and local authorities by providing a centralized platform for reporting, tracking, and resolving community issues.

The application supports **role-based access** for both citizens and authorities, enabling efficient complaint management from issue submission to final resolution.

---

# 1. Homepage

The homepage serves as the entry point of the application. It introduces the purpose of the platform and allows citizens to:

- Browse recently reported community issues
- Filter issues by **State**, **Category**, and **Status**
- Report a new issue
- Access the login page
- View publicly available complaints without authentication

The landing page promotes community participation and encourages citizens to report civic problems that require attention from local authorities.

---

# 2. Login & Role Selection

The system provides secure authentication for different user roles.

After successful login, users are automatically redirected according to their role:

### Citizen
- Report new issues
- View personal complaints
- Track complaint progress
- Submit feedback
- Confirm issue resolution

### Authority
- Access assigned complaints
- Update complaint status
- Add resolution comments
- Manage complaints within their jurisdiction

This role-based authentication ensures secure access to application features.

---

# 3. Citizen Dashboard

After logging in, citizens are redirected to their personalized dashboard.

Key features include:

- User profile menu
- Quick navigation to submitted complaints
- Report New Issue option
- Track issue progress
- View complaint history
- Logout functionality

The dashboard acts as the central workspace for managing all citizen interactions with the system.

---

# 4. Report Community Issue

Citizens can report a new issue using a comprehensive complaint form.

The form captures:

- Issue Title
- Category
- Detailed Description
- State
- Location
- Image Upload (optional)

Submitted complaints are validated, stored in the SQLite database, and assigned to the appropriate authority based on the selected state.

This structured reporting process ensures complete and accurate complaint information.

---

# 5. My Reported Issues

This module allows citizens to monitor every complaint they have submitted.

Each issue card displays:

- Issue title
- Category
- Current status
- Description preview
- Location
- Submission date
- Authority feedback
- Citizen feedback
- Resolution confirmation status

Additional actions include:

- View issue details
- Submit feedback
- Confirm successful resolution
- Report another issue

This module provides complete transparency throughout the complaint lifecycle.

---

# 6. Issue Details

Selecting **View Details** opens a detailed view containing complete complaint information.

Displayed information includes:

- Issue title
- Category
- Description
- Location
- Submission date
- Current status
- Authority comments
- Resolution updates

This feature allows citizens to stay informed about the progress of their reported issues.

---

# 7. Authority Dashboard

The Authority Dashboard provides government officials with tools to manage complaints efficiently.

Dashboard features include:

- Pending Issues
- Issues In Progress
- Resolved Issues Awaiting Confirmation
- State-wise filtering
- Complaint statistics
- Quick navigation between complaint categories

Authorities can efficiently monitor workloads and prioritize issue resolution.

---

# 8. Complaint Resolution Management

Authorities manage complaints through the resolution interface.

Available actions include:

- Review complaint details
- Update complaint status
- Mark issues as Pending, In Progress, or Resolved
- Add official comments
- Record resolution updates

Once an issue is marked as resolved, citizens are notified and can verify whether the reported problem has been successfully addressed.

This two-way confirmation process improves transparency and accountability.

---

# Complete System Workflow

The application follows a structured complaint management process:

```
Citizen Registration/Login
            ↓
Report Community Issue
            ↓
Store Complaint in SQLite Database
            ↓
Assign Complaint to Concerned Authority
            ↓
Authority Reviews Complaint
            ↓
Status Updated (Pending → In Progress → Resolved)
            ↓
Authority Adds Resolution Comments
            ↓
Citizen Views Updates
            ↓
Citizen Confirms Resolution & Provides Feedback
            ↓
Issue Successfully Closed
```

---

# Key Features Demonstrated

- Secure User Authentication
- Role-Based Access Control
- Citizen & Authority Modules
- Community Issue Reporting
- Complaint Tracking
- State-Based Complaint Allocation
- Category-Based Filtering
- Image Upload Support
- Complaint Status Management
- Authority Dashboard
- Resolution Workflow
- Citizen Feedback System
- Resolution Confirmation
- SQLite Database Integration
- Responsive User Interface
- Flask Backend with Jinja Templates

---

These screenshots collectively demonstrate the complete functionality of the Community Issue Reporting System, from citizen registration and complaint submission to authority management, issue resolution, citizen feedback, and final complaint closure.
