#  Task Management System

A full-stack Task Management System built with **Node.js**, **Express**, **MySQL**, and **Bootstrap**, designed to help individuals and teams organize, track, and manage their work efficiently.

##  Overview

The Task Management System allows users to:
- Register and manage accounts
- Create, assign, and track tasks
- Manage projects
- Collaborate with teams through comments and attachments
- Visualize progress through charts and reports

##  Deployed
**(Note: Deployment link expired)**  
Previously hosted on Railway: [https://se-production-13b7.up.railway.app/](https://se-production-13b7.up.railway.app/)

---

For full technical and functional details, refer to the accompanying  Word Project Documentation.

##  Features

###  User Account Management
- Registration with email verification
- Secure login/logout
- Profile editing and account deletion
- Password strength validation
- Role-based access (Admin, Member, Guest)

###  Task Management
- Task creation with priority, category, and deadlines
- Task editing, deletion, completion tracking
- Task filtering, sorting, and searching
- Deadline reminders via notifications
- Assign tasks to team members

###  Team Collaboration & Reporting
- Comment system per task with timestamps
- File attachments (PDF, images, etc.)
- Task assignment tracking
- Google Calendar integration
- Task progress visualization
- Task completion report (PDF/CSV)
- System usage analytics for admins

---

##  Technologies

### Frontend
- HTML, CSS, JavaScript, Bootstrap

### Backend
- Node.js, Express.js

### Database
- MySQL  
- Singleton pattern for DB connection

### Architecture
- MVC (Model-View-Controller)
- RESTful API structure

### Design Patterns
- **Singleton**: Efficient and consistent DB access  
- **Factory**: Object creation abstraction for tasks  
- **Observer**: Event-based updates/logs  
- **MVC**: Separation of concerns and maintainability

---

##  Database Structure

### Tables & Fields

| Table    | Fields                                                                 |
|----------|------------------------------------------------------------------------|
| `users`  | id, username, email, password, role                                    |
| `projects` | id, name, description, user_id                                       |
| `tasks`  | id, title, description, status, priority, due_date, user_id, project_id |

---

## 🧪 Testing

- Framework: **Jest**
- Focus: Unit tests for `UserModel` and `TaskModel`
- Location: `/tests/`
  - `tests/userModel.test.js`
  - `tests/taskModel.test.js`

### Tested Features
- User creation, retrieval, deletion
- Task creation, retrieval, deletion



##  Future Improvements

- JWT authentication
- Role-based access control for sensitive operations
- Better frontend UI/UX
- Integration and end-to-end tests
- CI/CD with GitHub Actions or similar
- Improved error handling and logging

---

##  Contributors

**Kerim Senderovic**  
> Rijad Basic

---

##  License

This project is for educational purposes and does not currently include a license.

---

## 📬 Contact

For any questions or suggestions, feel free to reach out via email or GitHub.

