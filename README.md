# CS-340-Client-Server-Development
CS 340 portfolio project featuring a MongoDB database, Python CRUD module, and interactive Dash dashboard for Grazioso Salvare.
## About the Project

For this project, I developed a dashboard for Grazioso Salvare that connects to a MongoDB database containing animal shelter data. The dashboard allows users to filter animals based on different rescue types and view the results through an interactive data table, breed chart, and geolocation map.

## Maintainable, Readable, and Adaptable Programs

I try to make my programs maintainable and readable by separating different parts of the program based on their purpose. In this project, I used the CRUD Python module from Project One to handle communication with MongoDB and then reused that module when developing the dashboard in Project Two. This made the dashboard code easier to work with because the database operations were kept separate from the user interface.

Another advantage is that the CRUD module can be reused instead of rewriting database code every time it is needed. In the future, I could use a similar module with other applications that need to create, read, update, or delete information from a MongoDB database.

## Approaching Problems as a Computer Scientist

I approach problems by breaking the requirements into smaller parts and working through them individually. For the Grazioso Salvare dashboard, I first made sure the application could communicate with the database and display the animal records. I then added the rescue filters, interactive table, breed chart, and geolocation map. Testing each component separately made it easier to find and fix problems.

This project was different from some of my previous assignments because multiple parts of the application had to work together. The database, Python code, and dashboard all depended on each other. For future database projects, I would continue breaking client requirements into smaller tasks, creating the necessary queries, and testing each feature before combining everything into the final application.

## What Computer Scientists Do and Why It Matters

Computer scientists use technology and programming to solve problems and make information easier to use. This can include developing applications, working with databases, analyzing information, and creating tools that help users complete tasks more efficiently.

For a company like Grazioso Salvare, this project makes it easier to search through a large amount of animal shelter data and identify dogs that may be good candidates for rescue training. Instead of manually searching through records, users can select a rescue type and quickly see matching animals along with useful charts and location information.
