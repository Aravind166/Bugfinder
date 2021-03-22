# Bugfinder
A software bug is an error, flaw or fault in a computer program or system that causes it to produce an incorrect or unexpected result, or to behave in unintended ways. The process of finding and fixing bugs is termed "debugging" and often uses formal techniques or tools to pinpoint bugs, and since the 1950s, some computer systems have been designed to also deter, detect or auto-correct various computer bugs during operations.  Most bugs arise from mistakes and errors made in either a program's design or its source code, or in components and operating systems used by such programs. A few are caused by compilers producing incorrect code. A program that contains many bugs, and/or bugs that seriously interfere with its functionality, is said to be buggy (defective). Bugs can trigger errors that may have ripple effects. Bugs may have subtle effects or cause the program to crash or freeze the computer. Other bugs qualify as security bugs and might, for example, enable a malicious user to bypass access controls in order to obtain unauthorized privileges

THATS WHY I HAVE DONE THIS EXCITING PROJECT TO REMOVE ALL BUGS FROM OUR CODES.
A Bug tracking and ticketing system using Django. This is the project with Python and JavaScript. 

Features
Create project.
Add or remove dev from project.
Issue & track bugs.
Assign dev to an issue.
Public bug issue url.
Developer's profile.
Reset password using email.

Files & Directories
Main Directory

bugbinder - Main application directory.

_auth - Authentication app.

models.py - ORM auth model. Contains an Code class which has user and hashed reset password code.
urls.py - Contains all url paths for authentication, like login, sign up, forget and reset password as well as logout.
views.py - Contains all view functions for authentication, like login, sign up, forget and reset password as well as logout.
_profile - Profile app for maintaining user's prolife.

models.py - ORM profile model. Contains an Profile class which has all information of a user.
urls.py - Contains all url paths for profile, like view, edit and delete profile as well as change password.
views.py - Contains all view functions for profile, like view, edit and delete profile as well as change password.
bugbinder - Containes settings and main url file.

core - Core app for all functionalities like create project, assign task etc.

models.py - Contains two classes Project and Task which has all information about the project and tasks(bugs).
urls.py - Contains all url paths for Project and Task control, like view dashboard, project, task. search add, assign and remove devloper. Delete task and project. Create bugs.
views.py - Contains all view functions for Project and Task (mentioned in urls.py).
static - Holds all static files.

css - Contain all css files for styling the website.
base.css - Common styles for all pages.
bug-issue.css - Styles for bug issue page.
colors.css - Colors in root section.
dashboard.css - Styles for dashboard page.
home.css - Style for home page with login, sign up and reset password.
profile.css - Style for profile page.
project.css - Style for project page.
task.css - Style for tasks page.
user.css - Style for other user profile page.
js - Contains all JavaScript files for manipulating the DOM with ajax functionalities.
img - Holds all static images and icons.
Templates - Holds all html files.

gitignore - Ignored files for git.

Pipfile - Project dependencies.

Justification
This project is distinct from all previous projects so far. Why?

More models with complex relation between them.
Uses ajax functionality, fetch data without reloading the page.
Send password reset code using email.
Saves hashed password reset code in db.
Uses Chart.js for showing the chart.
Completely Mobile responsive.
