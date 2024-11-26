# Task Manager Application (TMAP)
## Project Overview
Welcome to the Task Manager Application (TMAP)! This is a simple web-based tool designed to help users efficiently manage their tasks. The application features user authentication, task creation, task dashboards, and detailed views for managing and tracking tasks. The system is designed to be user-friendly and easy to navigate with a clean, responsive UI.

This application is built using HTML for the structure, CSS for styling, and is designed to be fully responsive to enhance user experience across various devices.

## Features
* **User Authentication:** Register and log in to access the task management system.
* **Task Creation:** Easily create new tasks with detailed descriptions.
* **Task Dashboard:** View a list of all tasks with the ability to access more details and manage tasks.
* **Task Details:** View detailed information about individual tasks.
* **Responsive Design:** The application adapts to various screen sizes, ensuring accessibility across mobile and desktop platforms.
## File Structure
The project is structured into multiple HTML files and assets to improve readability and maintainability. Below is a breakdown of the key files:
```
CT-MP_TMAP/
├── assets/
│   └── css/
│       └── styles.css          # Main stylesheet for the application
├── authentication.html         # User authentication (Login/Registration)
├── index.html                  # Homepage for the Task Manager Application
├── README.md                   # Project overview and instructions
├── register.html               # User registration page
├── task-creation.html          # Page for creating new tasks
├── task-dashboard.html         # Dashboard for viewing and managing tasks
└── task-details.html           # Page for viewing task details
```
## How to Set Up and Run the Application
1. **Clone the Repository:** To get started, clone the repository to your local machine:

```
git clone https://github.com/MatthewGUser/CT-MP_TMAP.git
cd CT-MP_TMAP
```
2. **Run the Application:** Since this is a front-end application, simply open any of the HTML files (e.g., `index.html`, `task-dashboard.html`, etc.) in your browser to view the app.

3. **Explore the Pages:**
* **Homepage** (`index.html`): The landing page of the Task Manager Application.
* **Authentication** (`authentication.html`): Users can log in or register to access their tasks.
* **Task Creation** (`task-creation.html`): Allows users to create new tasks.
* **Task Dashboard** (`task-dashboard.html`): Displays a list of tasks, with links to task details and editing options.
* **Task Details** (`task-details.html`): View and manage the details of a specific task.
## File Descriptions
`assets/css/styles.css`:
* Contains the styling for the entire application, ensuring a consistent and responsive layout.
`authentication.html`:
* Provides user login and registration functionality.
`index.html`:
* This serves as the main entry point or landing page of the application.
`register.html`:
* The registration page where new users can create an account.
`task-creation.html`:
* A page dedicated to creating new tasks and adding task details.
`task-dashboard.html`:
* The dashboard that displays all the tasks, with links to view, edit, or delete tasks.
`task-details.html`:
* A detailed page showing more information about a specific task, allowing further action or updates.
## How to Use the Application
1. Login / Register:
* Navigate to the authentication.html page to either log in or register a new user account.
2. Create a Task:
* After logging in, go to the task-creation.html page to create a new task. You will be able to add details such as task name, description, due date, etc.
3. View and Manage Tasks:
* Access the task-dashboard.html page to see all of your tasks in a list. Click on a task to view its details on the task-details.html page.
4. Responsive Design:
* The application is designed to be fully responsive. You can access it seamlessly on both desktop and mobile devices.
## Conclusion
The Task Manager Application is a simple yet effective tool for organizing and managing tasks. With a clean interface and an intuitive design, users can easily track, create, and view their tasks. Future improvements include adding user authentication, back-end integration, and more dynamic features.