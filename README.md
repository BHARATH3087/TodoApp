# TodoApp
#Bharath Todo List
I.          Requirements – Back-end:

a)        Framework: Use Flask or Django.

b)       API Endpoints:

a.        POST /categories: Add a new category (e.g., Work, Personal).

b.       GET /categories: Fetch all categories.

c.        POST /tasks: Add a task under a specific category (fields: title, description, category).

d.       GET /tasks: Fetch all tasks with an optional filter by category.

e.        PUT /tasks/: Update a task (e.g., mark as completed or edit details).

f.          DELETE /tasks/: Delete a specific task.

c)        Database:

a.        Use SQLite or PostgreSQL.

b.       Models:

                                                                              i.        Category: id, name.

                                                                            ii.        Task: id, title, description, category_id, status, created_at.

d)       Validation:

o   Ensure no empty titles for tasks or categories.

o   Prevent duplicate category names.

II.       Requirements – Front-end (AngularJS + CSS):

a)        Features:

o   Home Page: Display all tasks grouped by category.

o   Add/Edit Forms:

§  Allow users to create new categories.

§  Enable users to add tasks under specific categories.

§  Edit or delete tasks directly from the UI.

o   Filters: Add a dropdown to filter tasks by category.

b)       Design:

o   Use CSS to make the app clean and visually structured.

o   Ensure responsiveness for desktop and mobile views.

 
