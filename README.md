# My First n8n Project 🚀

This is my first hands-on project while learning n8n and workflow automation.

## About the Project

This workflow fetches task information from a public REST API, checks whether the task is completed, and routes execution through the True or False branch.

## Workflow Architecture

Manual Trigger → Edit Fields → HTTP Request → IF Node

- **True:** The task is already completed.
- **False:** The task is not completed yet.

## Workflow Screenshot

![My First n8n Workflow](screenshots/workflow-overview.png)

## Technologies Used

- n8n
- Docker Desktop
- REST API
- JSON
- Git and GitHub

## API Used

https://jsonplaceholder.typicode.com/todos/4

## What I Learned

- Building workflows using a Manual Trigger
- Making HTTP GET requests
- Working with JSON API responses
- Configuring Boolean conditions
- Handling True and False execution branches

## Future Improvements

- Add scheduled execution.
- Integrate notifications.
- Build more practical automation workflows.

---

*This is the first step in my n8n learning journey. More projects coming soon!*
