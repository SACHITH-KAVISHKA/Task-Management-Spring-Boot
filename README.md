# Task-Management-Spring-Boot
Simple task management appliction using Spring Boot


How to Run :- Right-click on the main class of TaskManagerApplication, then select run.Then it can access throgh 'http://localhost:8081' in web browser.

Postman ap test :-
                1. Create task :- POST - "http://localhost:8081/tasks"
                            {
                                "title": "Tmkesnsssssnt",
                                "description": "This is a test task",
                                "status": "Pending"
                            }
                2. Get all tasks :- GET - "http://localhost:8081/tasks"
                3. Get spesific task :- GET - "http://localhost:8081/tasks/{id}"
                4. Update task :- PUT - "http://localhost:8081/tasks/{id}"
                            {
                                "title": "Updated Task",
                                "description": "This is an updated task",
                                "status": "In Progress"
                            }
                5. Delete task :- DELETE - "http://localhost:8081/tasks/{id}"
