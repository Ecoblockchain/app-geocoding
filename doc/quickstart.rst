==========
Quickstart
==========

1. Get the source code cloning/forking the repository:

  git clone https://github.com/PyBossa/app-geocoding/

  Or download the ZIP file from this URL:

  https://github.com/PyBossa/app-geocoding/zipball/master

2. Then, you will only have to access the folder that will have two files:

  * **template.html** This is the view for your application, what the volunteer will see and interact with. This file includes the HTML structure plus the JavaScript that will interact with the PyBossa API to request new tasks and save the answers from the users.
  * **createTasks.py** This is the script that will allow you to create the application in PyBossa and several tasks for the user.
     
3. Create an account in http://pybossa.com (check the Register option!) or in
   your local server.
4. Check your profile, your user name in blue in the top bar, to get your **API-KEY**.
5. Copy the **API-KEY** so you can create the application and the tasks (modify the name if you want for the application) using the createTasks.py script.
6. Run the command python: createTasks.py -u http://pybossa.com -k **API-KEY**.
7. To see the application up and running, check in the top bar of http://pybossa.com the Applications field. Click it to show the dropdown menu, and select **urbanpark**. This will open the application and you will be able to submit some results.
