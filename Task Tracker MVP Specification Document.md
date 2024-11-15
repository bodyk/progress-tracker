# Task Tracker MVP Specification Document

## 1. Core Functionalities

- **Task Creation**:
  - **Description**: Users can create a new task by specifying a title and description.
  - **Requirements**: Each task requires a title (mandatory) and a description (optional).

- **Task Categories**:
  - **Description**: Users can categorize tasks for better organization (e.g., “Work,” “Personal”).
  - **Requirements**: Categories are user-defined, with an option to add, edit, or delete categories.

- **Task Status Tracking**:
  - **Description**: Users can track the progress of tasks by updating their status.
  - **Requirements**: Status options are “To Do,” “In Progress,” and “Done.”

---

## 2. Application Type

- **Web Application**: The initial application will be a web-based solution accessible via a browser.

---

## 3. User Access

- **Single-user**: The application will initially be developed for single-user access.

---

## 4. Data Storage

- **Local Database**: Data will be stored locally in a SQL Server database for the MVP. This database may later be moved to a cloud-based solution for synchronization and backups.

---

## 5. Reminders and Notifications

- **To be determined (TBD)** for the MVP. Potential options include in-app notifications, email, or other channels in future iterations.

---

## 6. Additional MVP Features

- **Task Goals**:
  - **Description**: Users can set financial goals associated with tasks. For instance, completing certain tasks may result in earning a designated amount of “money,” which can then be put toward predefined goals.
  - **Requirements**:
    - Tasks can be assigned a monetary value for completion.
    - Users can create, view, edit, and delete goals (CRUD functionality) that the task earnings can contribute to.
    - Display the progress toward each goal based on task earnings.

---

## 7. Analytics and Insights

- **Progress Toward Goals**:
  - **Description**: Users will see their progress toward achieving financial goals based on task completion.
  - **Requirements**:
    - Track money earned per completed task.
    - Show percentage progress toward a set financial goal.

---

## 8. Technology Stack

- **Backend**: ASP.NET Core for the API and business logic.
- **Database**: SQL Server for storing task, category, status, and goal data.
- **Frontend**: React for the user interface.

---

## 9. Design and User Experience

- **Intuitive and Visually Appealing**: The design should focus on ease of use with an appealing layout, making it simple for users to manage tasks and track goal progress.

---
