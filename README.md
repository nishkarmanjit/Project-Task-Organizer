# Task Organizer

## Project Description

### Overview
Task Organizer is a simple yet efficient application built to manage tasks seamlessly. Users can add, update, delete, and view tasks along with their deadlines. The application categorizes tasks into three statuses: **Pending**, **Completed**, and **Overdue**, enabling users to prioritize their tasks effectively.

### Features
- Add tasks with a description and deadline.
- Update tasks to mark them as **Completed** or **Pending**.
- Delete tasks that are no longer needed.
- Automatically categorize tasks as **Pending**, **Completed**, or **Overdue** based on deadlines.
- View and sort tasks by deadline.

---

## Revision History
| Date       | Change Description     | Author                |
|------------|------------------------|-----------------------|
| 2024-10-30 | Initial draft created  | Nishkarmanjit Kaur   |

---

## System Overview

### Purpose
This document provides an overview of the high-level requirements and architecture for the **Task Organizer** application. It is intended for developers, project managers, and testers involved in building or maintaining this system.

### Scope
The Task Organizer app is designed to:
- Enable task management via a user-friendly interface.
- Store task data locally using browser storage (e.g., LocalStorage) or a lightweight database like SQLite.
- Prioritize simplicity, ensuring core task functionalities are robust.

### Non-Functional Scope
- No reminders or task-sharing capabilities are included in this version.
- No authentication is required.

---

## Requirements

### Functional Requirements
1. Allow users to add tasks with a title, description, and deadline.
2. Enable users to mark tasks as **Completed** or **Pending**.
3. Automatically categorize tasks as **Pending**, **Completed**, or **Overdue**.
4. Provide functionality to delete tasks.
5. Allow sorting of tasks by their deadlines.

### Non-Functional Requirements
- **Performance**: All operations (add, update, delete, view) must execute within 2 seconds.
- **Reliability**: The app should ensure 99% uptime and robust interaction handling.

### Technical Stack
- **Frontend**: HTML, CSS, JavaScript (Vanilla or React.js)
- **Backend (Optional)**: Node.js with Express.js
- **Database**: SQLite or LocalStorage
- **Environment**: Compatible with any modern browser or a local Node.js server.

---

## Data Design

### Task Entity
| Field      | Type       | Description                           |
|------------|------------|---------------------------------------|
| TaskID     | Integer    | Unique identifier for each task.      |
| Title      | String     | Short, descriptive title of the task. |
| Description| String     | Detailed explanation of the task.     |
| Deadline   | Date       | Deadline for task completion.         |
| Status     | String     | Task status: Pending, Completed, Overdue.|

---

## Folder Structure
```plaintext
Task-Organizer/
├── public/
│   ├── index.html
├── src/
│   ├── components/
│   │   ├── TaskList.js
│   │   ├── AddTaskForm.js
│   │   ├── TaskItem.js
│   ├── styles/
│   │   ├── styles.css
│   ├── App.js
│   ├── index.js
├── package.json
├── README.md

## User Interface Design

### Navigation Flow
- **Main Screen**: Displays a list of tasks.
- **Add Task**: Opens a form to input task details.
- **View Task**: Shows task details, including status and deadline.
- **Edit Task**: Enables modification of task details.
- **Delete Task**: Removes tasks from the list.

---

## Quick Start

### Prerequisites
- Node.js installed on your machine.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Task-Organizer.git
   cd Task-Organizer
Task-Organizer/
├── public/
│   ├── index.html
├── src/
│   ├── components/
│   │   ├── TaskList.js
│   │   ├── AddTaskForm.js
│   │   ├── TaskItem.js
│   ├── styles/
│   │   ├── styles.css
│   ├── App.js
│   ├── index.js
├── package.json
├── README.md

## User Interface Design

### Navigation Flow
- **Main Screen**: Displays a list of tasks.
- **Add Task**: Opens a form to input task details.
- **View Task**: Shows task details, including status and deadline.
- **Edit Task**: Enables modification of task details.
- **Delete Task**: Removes tasks from the list.

---

## Quick Start

### Prerequisites
- Node.js installed on your machine.

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/Task-Organizer.git
   cd Task-Organizer

