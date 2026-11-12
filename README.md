Task API

A simple CRUD API built using FastAPI for the FlyRank Assignment.

Features

Create a task
Read all tasks
Read a task by ID
Update a task
Delete a task
Health check endpoint
Automatic Swagger documentation

Installation

pip install -r requirements.txt

Run the Application

uvicorn main:app --reload
The API will be available at:

http://127.0.0.1:8000
Swagger Documentation:

http://127.0.0.1:8000/docs

API Endpoints

Method	Endpoint	Description
GET	/	Root endpoint
GET	/health	Health check
GET	/tasks	Get all tasks
GET	/tasks/{task_id}	Get task by ID
POST	/tasks	Create a task
PUT	/tasks/{task_id}	Update a task
DELETE	/tasks/{task_id}	Delete a task

Example Task

{
  "id": 1,
  "title": "Learn FastAPI",
  "done": false
}       