# Project Management App

## Overview

Welcome to the Project Management App! This application is designed to help you efficiently manage your projects and tasks. With an intuitive interface and robust functionality, it provides a seamless experience for organizing your work.

## Features

- **Project Management:** Create, select, and delete projects with ease.
- **Task Management:** Add and delete tasks within each project to keep track of your to-dos.
- **Dynamic Interface:** Conditional rendering to provide different views based on the selected project state:
  - No Project Selected: Prompt to start adding a new project.
  - New Project: Interface for adding a new project.
  - Selected Project: Detailed view of the selected project with task management features.
- **State Management:** Efficient state management using React's `useState` hook to handle project and task operations.



## How to Use

1. **Add a Project:**
   - Click the "Add Project" button in the sidebar.
   - Fill in the project details in the form displayed.
   - Click "Add" to save the project or "Cancel" to discard.

2. **Select a Project:**
   - Click on a project from the sidebar to view its details and tasks.

3. **Add a Task:**
   - Within the selected project view, enter the task text in the input field.
   - Click "Add Task" to save the task.

4. **Delete a Task:**
   - Click the "Delete" button next to a task to remove it from the project.

5. **Delete a Project:**
   - In the selected project view, click the "Delete Project" button to remove the project and all its associated tasks.

## Installation

1. Clone the repository: `git clone https://github.com/Vishal-Tiwari-11/React-Project-Management-App.git`
2. Navigate to the project directory: `cd project-management-app`
3. Install dependencies: `npm install`
4. Start the application: `npm start`


## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.


Thank you for using the Project Management App! We hope it helps you stay organized and productive. If you have any questions or feedback, feel free to reach out.
