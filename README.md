# work-station

Assessment for a Job Application.

//PROJECT
Create a simple Web application (Nodejs - Express)
Requirement:

1. User can register and login with username, password, and email.
2. User can create a workspace to work with.
3. In every workspace, user can create task with a compulsory deadline (date and time).
4. The task can be set as completed or incomplete and the status is shown in a task view.
5. Incomplete task must show how far time to deadline in human readable way. eg: (2 days 5 minutes remaining).
6. Completed task need to show when was the task has been completed in human readable way. eg: (2 days ago, 5 minutes ago).
7. Each workspace and task must be protected that another user can't access that workspace and task.

//WORKS

Made using MERN Stack.

To begin the Web App

1. Go to folder main folder "work-station-v3". Via Bash command, type "npm start" and run.
2. Next go to folder "client". Via Bash command, type "npm start" and run.

Using Web App
1. You may fill in your credentials upon signing up. Data collection will be saved in mongoDB (server provided).
2. As you sign in, you will enter the work station Ui.
3. You may logout when done.

//IN-PROGRESS
1. Add Task is complete but the the List of Task have not been listed properly. If we refresh page, it will load.

//COMPLETE
1. User login credentials are saved in a MongoDB server.
2. User does not share the same work stations & task.
3. The Task List are protected betweeen Users.

//INCOMPLETE
1. Add Task to individual Work Station.
2. Create individual Work Station.
3. Add task with individual timer countdown
4. Work Station with collected timer countdown based on total task added.
5. Create a list of Completed Task and Incomplete Task.
6. Clean Ui represntation.
