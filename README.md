# Project Management Application

The Project Management App is a web-based application designed to simplify project management tasks and facilitate collaboration among team members. With features like project creation, todo management, and export summary as Gist, this app provides a comprehensive solution for managing projects efficiently.

## Features

- **User Authentication**: Secure login functionality ensures that users can access their projects securely.
- **Project Management**:
  - Create new projects with a unique identifier, title, and creation date.
  - List all projects on the home page for easy access.
  - View detailed project information including title and list of todos.
- **Todo Management**:
  - Add new todos to a project with a unique identifier, description, status, creation date, and last updated date.
  - Edit existing todos to update their status.
  - Mark todos as complete or pending.
- **Export Summary as Gist**:
  - Generate project summary in markdown format.
  - Export the summary as a secret gist on GitHub with the following format:
    - File name: `<Project title>.md`
    - Project title as heading.
    - Summary: `<No. of completed todos> / <No. of total todos>` completed.
    - Section 1: Task list of pending todos (with an open checkbox).
    - Section 2: Task list of completed todos (with a checked box).
   
## Technologies Used
- Backend: Java (with Spring Boot)
- Frontend: HTML, CSS, JavaScript
- Database: MongoDB

![Screenshot 2024-06-14 100258](https://github.com/fayazap/Todo/assets/84265684/552563fd-60d6-4938-9c79-a2cd0618f3bd)
![Screenshot 2024-06-14 100245](https://github.com/fayazap/Todo/assets/84265684/d11fde83-e73c-48f9-9c31-e945b3a6f210)
![Screenshot 2024-06-14 100234](https://github.com/fayazap/Todo/assets/84265684/8070094b-e94f-467b-a485-67ee1fb0eee1)

