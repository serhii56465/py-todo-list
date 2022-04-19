# py-todo-list

In this exam project you have to implement todo list site.

You should have such models:
1. Task - todo list is consist of tasks. Each task should have fields for:
    - content - describes what you should do.
    - datetime, when task was created
    - optional deadline datetime if task should be done until some 
datetime
    - boolean field that mark if task is done or not
    - tags that are relevant for this task
2. Tag - tag symbolize the theme of the task, consist only of name.

Task can have multiple tags and tag can be in multiple tasks.

Create the home page. Home page is accessed by `127.0.0.1:8000/`, there you 
should have:
1. Sidebar with the links to:
   - Home page
   - Tag list page
    sidebar should be on all pages.
2. Todo list which is a list of tasks. 
   - Tasks should be ordered from newest to oldest
   - All task information should be displayed. 
   - There should be a button to add a new task. 
   - For each task add links for updating and deletion. 
   - Also, add button `Done` if task is not done and `Not done` if task is 
done, this button changes status of the task to the opposite and redirects 
to this page.

Home page should look like this: 

Create tag list page. Tag list page is accessed by `127.0.0.1:8000/tags/`, 
there you should have:
1. Table with tags names, links for updating and deletion.
2. Button to add a new tag.

Tag list page should look like this:

That's all!
