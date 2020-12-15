# Exam-Results-Portal
Exam Results Portal
 
This is a Web Application where Teachers are able to Upload the students results and also able to see the Results.
 
Technologies Used :
Frontend:     Angular, Html5, SCSS, Bootstrap4, Angular Material.
Backend:      .Net Core.
Database:     SqlServer
 
Teachers are able to login to the application.
Authentication is done using JWT.
 
This application consist of mainly 3 sections-
 
1.     Web Client :- This is the UI part of the Application where teachers are able to login, view and edit the results and other details of the students.
 
2.     Web Api :- Rest API to act as intermadiate between web client and DB
 
3.     Database :- Store information about teachers and students

Steps To Run
DB Script -> Execute DB script over Sql server managemnt studio so it will craete DB and tables along with data
Core Api Service -> extract ExamResultsPortalWebAPI.zip and open .sln file in visual sudio to host application over server like IIS, IIS Epress
Angular Web Client ->  extract ExamResultsPortalClient.zip and open solution in visual studio code and execute command below 
		1) npm install
		2) npm start
browes application over any browser to view web client

Note -> default users details
1) 'sshanmugam@presidio.com' with passowrd '12345'
2) 'karanshinde@gmail.com' with password 'karan123'
