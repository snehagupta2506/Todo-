Todo list web application using MERN stack is a project that basically implements basic CRUD operation using MERN stack (MongoDB, Express JS, Node JS, React JS). The users can read, add, update, and delete their to-do list in the table using the web interface. The application gives a feature to the user to add a deadline to their task so that it user can be reminded of the last day to complete the project
Technologies used / Pre-requisites:
MongoDB
Express JS
React JS
Node JS
HTML, CSS, JavaScript

Requirements:
Node.js installed in your machine.
MongoDB installed locally or use MongoDB Atlas online.
Code editor : VS code

Approach to create Todo List:
In frontend, the react component called “Todo” is used to display tasks, deadlines and its status and form to add new todo item with edit and deletion feature.
In backend, application fetches data from MongoDB using backend API called “/getTodoList”. New data can be added to the database using “/addTodoList” API. “/updateTodoList/:id” API is used to edit the existing specific data from the table. “/deleteTodoList/:id” API is used to delete the specific data from the table.

Functionalities Of Todo Application:
Add new todo: User can add new todo task using the form. On clicking “submit” button, The new data will be saved to database.
Display todo list: User can view the todo list in table format.
Edit existing data: User can click on “Edit” button to make the table row to editable fields. On clicking “Edit” button, new buttons call “Save” and “Reset” will be created. “Save” button is to update the edited data to database. “Reset” button is to reset the data in the field.
Delete existing data: User can click on “Delete” button available in the table row to delete the data from database.

Steps to create the project:

Step 1: Create directory for project.

mkdir Todo-List
Step 2: Create sub directories for frontend and backend.

Open Todo-List directory using following command.

cd Todo-List
Create separate directories for frontend and backend.

mkdir frontend
mkdir backend
Use “ls” command to list created folders.

ls
Step 3: Open backend directory using the following command.

cd backend
Step 4: Initialize Node Package Manager using the following command.

npm init
npm-init-backend
Initialize npm in backend

Step 5: Install express, mongoose and cors package in backend using the following command.

npm install express mongoose cors
Step 6: Come back to Todo-List folder (project main folder).

cd ../
Step 7: Open frontend directory using the following command.

cd frontend
Step 8: Create react application in the current directory using the following command.

npx create-react-app .
Step 9: Install bootstrap, axios and react-router-dom package in backend using the following command.

npm install bootstrap axios react-router-dom
Step 10: Open Todo-List using your familiar code editor.

Come back to Todo-List folder (project main folder).

cd ../

code .

Steps to run application:

Step 1: Open Todo-List/backend folder in new terminal / command prompt.

Step 2: Execute the command to start backend API server.

npm start
Now, our backend server is running in localhost on port 3001.

http://localhost:3001/
Step 3: Open Todo-List/frontend folder in another new terminal / command prompt.

Step 4: Execute the following command to run react app.

npm start
Open the browser and navigate to the following link to open the application.

http://localhost:3000/
