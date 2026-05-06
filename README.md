# Smart Task Manager API 🚀

Smart Task Manager API is a backend task management application built using Python. It allows users to create tasks, view all tasks, and update task completion status efficiently. The project demonstrates backend development concepts such as API routing, database integration, CRUD operations, and data persistence.

## Objectives
- Learn backend development using Python
- Understand REST API architecture
- Perform CRUD operations
- Integrate database with backend
- Learn ORM concepts
- Build a scalable project structure

## Tech Stack
- Python
- FastAPI
- SQLAlchemy
- SQLite
- Visual Studio Code
- GitHub

## Features
✅ Create new tasks  
✅ View all tasks  
✅ Mark tasks as completed  
✅ Permanent database storage  
✅ Interactive API documentation  

## Project Structure
```bash
task-manager/
│── main.py
│── database.py
│── models/
│   └── models.py
│── tasks.db
│── requirements.txt
│── README.md
```

## API Endpoints
- **GET /** → Check API status  
- **POST /tasks** → Create new task  
- **GET /tasks** → Fetch all tasks  
- **PUT /tasks/{task_id}** → Mark task complete  

## How It Works
The user sends a request through the API interface, FastAPI processes the request, SQLAlchemy handles database operations, and SQLite stores or retrieves task data permanently.

## Future Enhancements
- Delete task feature  
- User login/signup  
- Task categories  
- Due dates & priority labels  
- Frontend integration  
- Cloud deployment  

## Learning Outcomes
This project helped in understanding Python backend development, FastAPI routing, database connectivity, SQLAlchemy ORM, and CRUD operations.

## Author
**Anshika Singh**  
BTech – Computer Science Engineering
