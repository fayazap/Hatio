![Screenshot 2024-06-14 100234](https://github.com/fayazap/Todo/assets/84265684/ebaa8cc5-9bf2-4688-80ba-c9c1535040f4)# Project Management Application

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


![Screenshot 2024-06-14 141147](https://github.com/fayazap/Todo/assets/84265684/4a7597d0-b3a1-4576-8c58-8133c2b76add)
![Screenshot 2024-06-14 100245](https://github.com/fayazap/Todo/assets/84265684/85b6434a-ece5-4fa4-9d1b-94f697734be7)
![Screenshot 2024-06-14 100234](https://github.com/fayazap/Todo/assets/84265684/6d4a0ea6-dc7d-4f56-ab42-5d9c6469e39c)


