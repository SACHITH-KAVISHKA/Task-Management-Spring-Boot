# Task-Management-Spring-Boot
Simple task management application using Spring Boot


<h3>How to Run:-</h3><br> Right-click on the main class of TaskManagerApplication, then select run. Then it can be accessed through 'http://localhost:8081' in the web browser.<br>

Postman ap test:-<br>
                1. Create task :- POST - "http://localhost:8081/tasks"
                            {<br>
                                "title": "Tmkesnsssssnt",<br>
                                "description": "This is a test task",
                                "status": "Pending"<br>
                            }<br>
                2. Get all tasks:- GET - "http://localhost:8081/tasks"<br>
                3. Get specific task :- GET - "http://localhost:8081/tasks/{id}"<br>
                4. Update task :- PUT - "http://localhost:8081/tasks/{id}"<br>
                            {<br>
                                "title": "Updated Task",<br>
                                "description": "This is an updated task",<br>
                                "status": "In Progress"<br>
                            }<br>
                5. Delete task :- DELETE - "http://localhost:8081/tasks/{id}"
