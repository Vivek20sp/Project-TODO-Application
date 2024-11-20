# ReactJS-ToDoList
## Introduction
This project implements the Full Stack for a simple Project-To-Do List web application, using the React JS library, and also Styled Components replacing pure CSS.<br/>
It includes the login page and the general UI of the app. <br/>
The login authentication logic and the tasks database for each user are not implemented, since this project aims to be a Full Stack Application.

## Inspiration
The login page was inspired in [this design](https://dribbble.com/shots/17564792-Log-in-page-Untitled-UI/attachments/12710737?mode=media) by Jordan Hughes.
The home page was inspired in [this design](https://dribbble.com/shots/14440819-KosmoTime-Task-Manager/attachments/6121947?mode=media) by Mik Skuza.

# Todo Management Application with GitHub Gist Export

This application is a comprehensive Todo Management System that allows users to manage projects and their associated tasks. It includes features for creating, updating, and exporting project summaries as secret gists on GitHub in Markdown format.

---

## Features

### 1. **User Authentication**
- Basic authentication for user login.
- Secure access to all project management functionalities.

### 2. **Project Management**
- **Create a New Project**: Users can start a new project with a unique title.
- **List All Projects**: View all created projects on the home page.
- **View Project Details**: Select and view detailed information about a specific project.

### 3. **Todo Management**
Within a project, users can:
- **Add Todos**: Create new tasks with a description.
- **Edit Todos**: Update the description or status of an existing todo.
- **Mark Todos as Complete/Pending**: Change the status of a task.
- **Delete Todos**: Remove tasks that are no longer needed.

### 4. **Export Project Summary**
- Generate a project summary in **Markdown** format.
- Export the summary as a **secret gist** on GitHub.
- Save the exported Markdown file locally.

---

## Gist Format

### File Name
`<Project Title>.md`

### Markdown Format
```markdown
# Project Title

## Summary
<No. of completed todos> / <No. of total todos> completed.

### Pending Tasks
- [ ] Todo 1
- [ ] Todo 2

### Completed Tasks
- [x] Todo 3
- [x] Todo 4
```

### Usage
If you want to try this project yourself:
1. Install Node on your machine, via https://nodejs.org/en/.
2. Install Yarn on your machine via terminal command: `sudo npm install -g yarn`
3. Install Git on your machine, via https://git-scm.com/downloads.
4. Clone this repository to your machine. (more on how to do this [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository))
5. Run ```yarn install``` on the terminal, inside the folder where you downloaded the project, to install all used dependencies.
6. Run `yarn start` to run the project on your browser.




