# Sports-Management-Application
 The Sports Management System is a web-based application designed to manage tournaments, teams, venues, matches, and results efficiently. It allows admins to:  Create, update, and delete entities such as matches, venues, and teams. Track match logs and display details using interactive forms and stored procedures. Provide insights such as venues for the latest matches using advanced queries.

CRUD Operations:
Create, Read, Update, and Delete for matches, teams, venues, tournaments and results.
Match Management:
Schedule, edit, or delete matches with venue and team integration.
Venue Insights:
Nested query to display the venue of the latest match.
Dynamic Stored Procedures:
Manage database interactions efficiently for matches table.
Match Logs:
Automatically log match details for record-keeping using Triggers.
Admin Dashboard:
Access all functionalities from a central interface.
User Dashboard:
Access to only existing tounaments and results for matches.

Technologies Used:
Frontend:HTML5, CSS3, JavaScript
Backend:PHP
Database:MySQL (with stored procedures, triggers, and advanced queries)
Tools:phpMyAdmin , XAMPP for local development

Setup and Installation
Follow these steps to set up the project locally:

Prerequisites:
PHP (version>=7.4)
MySQL (version>=5.7)
A web server (e.g., Apache)
XAMPP or WAMP for local development

How to Run:
If using XAMPP, place the project folder in the htdocs directory.
Start Apache and MySQL in the XAMPP control panel.
Access the project at http://localhost/sports-management-system/.

Future Enhancements:
User Roles: Add roles for non-admin users to view match schedules.
Reports: Generate downloadable reports for matches and results.
Player Management: Include player details for each team.
Notifications: Add email or SMS notifications for scheduled matches.
