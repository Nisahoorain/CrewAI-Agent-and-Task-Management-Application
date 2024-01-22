**CrewAI Agent and Task Management Application**

**Introduction**

The CrewAI Agent and Task Management Application is a Flask-based web application designed to manage and execute tasks using AI agents. This application allows users to create AI agents with specific roles and goals, assign tasks to these agents, and execute these tasks. It is built to showcase the interaction between users, AI agents, and task management in a simple and intuitive interface.

**Features**

Set OpenAI API Key:
Allows the application to interact with OpenAI's services.

Create AI Agents: 
Define AI agents with specific roles, goals, and other characteristics.

Assign Tasks:
 Assign tasks to created AI agents.

Task Management: 
View, delete, or reassign tasks.

Execute Tasks:
 Run selected tasks and view the output.

**Prerequisites**
Before you begin, ensure you have met the following requirements:

Python 3.x installed on your system.

Flask library installed (pip install flask).

Visual Studio Code (VS Code) installed for code editing and execution.

Basic understanding of Python, Flask, and VS Code.

**Installation**

Installing Visual Studio Code

Download VS Code: Go to the VS Code website and download the appropriate version for your operating system.

Install VS Code: Follow the installation instructions specific to your OS.

**Setting Up the Application
**Clone or Download the Code: Clone or download the code from the repository.

Open the Application in VS Code: Open VS Code, go to File > Open Folder, and select the application's directory.

Install Required Python Packages: Open the terminal in VS Code (Ctrl+`) and run pip install flask.

Install CrewAi :- pip install crewai
**Setting** Up

Set the OpenAI API Key: Before using the application, set the OpenAI API Key. The application provides a form to enter and save this key. Ensure you have a valid OpenAI API key.

Run the Application: Start the Flask server by running python app.py in the VS Code terminal.

Usage

Accessing the Application

Once the server is running, open a web browser and navigate to http://127.0.0.1:5000/. The CrewAI Agent and Task Management interface should appear.


Setting OpenAI API Key

Navigate to the "Set OpenAI API Key" section.

Enter your OpenAI API key in the provided field.

Click "Set API Key".

Creating an AI Agent

Go to the "Add a CrewAI Agent" section.

Fill in details such as Role, Goal, Verbose, Backstory, and Allow Delegation.

Click "Add Agent".

Assigning a Task

Navigate to the "Assign a Task for CrewAI Agent" section.

Select an agent from the dropdown.

Enter the Task Name and Description.

Click "Add Task".

Managing Tasks

View tasks in the "Tasks for CrewAI Agents" section.

Use buttons next to each task to delete or reassign.

Executing Tasks

Select tasks for execution in the "Tasks for CrewAI Agents" section.

Choose the output format (Verbose, Console, or Both).

Click "Execute".

Observe the execution status and results.

**Troubleshooting**

Flask Installation: If the application doesn't run, ensure Flask is installed (pip install flask).

OpenAI API Key: Confirm the API key is valid and set if there are issues with AI agent interactions.

VS Code Issues: Ensure VS Code is correctly installed and the project folder is properly opened.

**Conclusion**
This application provides a foundational framework for managing and executing tasks with AI agents. It can be extended and customized to fit specific needs and requirements.
