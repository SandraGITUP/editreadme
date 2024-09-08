ShipOnline System - Project1

Name: Sandra Subhash
Student ID: 105066913
Project: ShipOnline System - Project 1
URL for Project 1:https://mercury.swin.edu.au/cos80021/s105066913/Project1/
Instructions for Using the Interface:
       #Homepage (shiponline.php):
       The homepage welcomes users to the ShipOnline System.
        Links to register new users, log in existing users, and access administrative functions are provided.
     #New User Registration (register.php):
        New users can navigate to the registration page by clicking the Registration link on the homepage.
        After completing the registration form with name, email, password, and phone number, users will be assigned a unique customer number.
        The system ensures email uniqueness and displays a confirmation message after successful registration.
   #Existing User Login (login.php):

Existing users can log in via the Log-In link on the homepage.
After entering a valid customer number and password, users are redirected to the Request Page (request.php).
  #Shipping Request Page (request.php):

Logged-in users can submit a shipping request by providing item details (description and weight), pick-up information, and delivery information.
The system verifies inputs and calculates the cost of shipping based on weight:
$20 for 0-2 kg.
$3 for every additional kg above 2 kg.
If all inputs are valid, the system generates a unique request number, confirms the request, and sends a confirmation email to the customer.
  #Administrator Access (admin.php):

Administrators can access the admin page via the Administration link on the homepage.
The admin page allows viewing customer requests by either request date or pick-up date.
Detailed information such as customer number, item description, and delivery details is displayed for each request.
List of Files in the System:
PHP Files:

shiponline.php: The homepage, providing links for registration, login, and administration.
register.php: Handles the registration process for new users.
login.php: Manages the login process for existing users.
request.php: Allows logged-in users to submit shipping requests and calculates the shipping cost.
admin.php: Displays all customer requests to administrators based on request or pick-up date.
*Additional Files:
checklist.docx: A checklist document to ensure all project requirements are met.
mysql_commands.txt: Contains the MySQL commands used to create the necessary database tables.
readme.txt: This file provides instructions for using the system and details about its components.
*MySQL Tables:
customers table: Stores customer details such as customer number, name, email, password, and phone number.
requests table: Stores all shipping requests, including request number, item details, pick-up and delivery information, and the customer number.
The MySQL commands for creating these tables are included in the file mysql_commands.txt.

