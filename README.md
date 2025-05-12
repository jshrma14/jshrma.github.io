# To-Do App

## Overview
The To-Do App is a Flask-based application designed to help users manage their tasks efficiently. It allows users to add, view, update, and delete tasks, providing a streamlined way to organize daily activities.

## Features
- Add new tasks
- View all tasks
- Update existing tasks
- Delete tasks
- Mark tasks as completed

## App Flow
```mermaid
graph TD
    A[Start] --> B[Add Task]
    A --> C[View Tasks]
    A --> D[Update Task]
    A --> E[Delete Task]
    B --> F[Task Added]
    C --> F
    D --> F
    E --> F
    F --> A
```

## Requirements
- Python 3.x
- Flask
- Flask-SQLAlchemy

## How to Run
1. Clone the repository.
2. Navigate to the `to-do app` directory.
3. Install the required dependencies using the command:
   ```
   pip install -r requirements.txt
   ```
4. Run the Flask application using the command:
   ```
   python app.py
   ```

## Future Enhancements
- Add a graphical user interface (GUI).
- Integrate with a persistent database.
- Add user authentication for personalized task management.python app.py