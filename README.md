# DO IT: a To-Do List Application

![Captura de pantalla 2024-11-26 112721](https://github.com/user-attachments/assets/a1a1305f-84f4-47b8-b142-777448bd4121)

## Overview
This project is a "To-Do List" application built on the **Bubble.io** platform, with backend workflows partially integrated using **Xano**. The application includes user authentication, enabling personalized task management for each user. The design follows a clean, minimalistic approach to ensure a user-friendly experience while meeting the project requirements.

## Features

### 1. Data Modeling:
  - **Task Name:** Text field for the task description.
  - **Due Date:** Date field to track deadlines.
  - **Completion Status:** Boolean indicates whether the task is completed.
- Established a one-to-many relationship between users and their tasks.

### 2. User Authentication:
- Implemented Bubble.io's built-in user authentication system:
  - Only authenticated users can access their tasks.

### 3. User Interface (UI):
- Designed a minimalistic and responsive interface with the following functionalities:
  - **Task Management:** Add, edit, delete tasks, and mark them as completed. Completed tasks are visually distinguished with a check mark and to-do tasks with a circle icon.
  - **User Dashboard:** Users can view and manage their personal task lists after logging in.
  - **API Integration Page:** A separate page displays tasks retrieved from Xano’s API.

### 4. Xano Integration:
- Configured Xano to provide an API endpoint that retrieves task data.
- Integrated the API with Bubble.io workflows to display the retrieved tasks on a dedicated page.

### 5. Bonus Features:
- Responsive design.

![Captura de pantalla 2024-11-26 112813](https://github.com/user-attachments/assets/5dce67b2-f12d-40c4-a2c4-1da7e941b88f)

## **Limitations and Pending Work**
**The Xano API retrieves tasks from a separate database, which does not synchronize with Bubble.io's database. This means the tasks displayed from Xano differ from those managed within the Bubble.io app.**
- **Next Steps:**
  - **1. Unify the data between Bubble.io and Xano to ensure consistency.**
  - **2. Enhance authentication with role-based access control for more advanced security.**

## Usage Instructions
1. **Access the Application:** [DO IT App](https://to-do-app-99050.bubbleapps.io/version-test?)
2. Sign up or log in to create a personalized task list.
3. Use the main interface to manage your tasks (add, edit, delete, mark as completed).
4. Visit the API integration page to view tasks retrieved from Xano.

## Design Approach
The application was designed with a clean and minimalistic aesthetic to ensure ease of use.

## Thank you for reviewing my project. 

---

**Cindy Gnaedinger** 
[LinkedIn](https://www.linkedin.com/in/cindygnaedinger/) |
cyn.gnaedinger@gmail.com
