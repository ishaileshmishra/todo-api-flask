# Flask: a famous python web framework

A brief introduction to the Flask todo-api

Our tasks resource will use HTTP methods as follows:

* HTTP Method	URI	Action 

- GET	http://[hostname]/todo/api/v1.0/tasks	Retrieve list of tasks
- GET	http://[hostname]/todo/api/v1.0/tasks/[task_id]	Retrieve a task
- POST	http://[hostname]/todo/api/v1.0/tasks	Create a new task
- PUT	http://[hostname]/todo/api/v1.0/tasks/[task_id]	Update an existing task
- DELETE	http://[hostname]/todo/api/v1.0/tasks/[task_id]	Delete a task
