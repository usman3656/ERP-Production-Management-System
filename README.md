# SE - Production Management System

created in 2022

## Abstract

The purpose of the project is to streamline the production management system of an existing business, (ZM Corporation). This project proposes a technical solution to improve ZM Corporation's production management to make it easier for them to go through the information and make informed decisions based on the information provided.

Additionally, the project would assess whether the current system should be moved to a different architecture, such as a web-based system, an ERP-based system, a native desktop app, etc. At its conclusion, the project would select an architecture and show how to execute it to meet the needs of ZM Corporation. A native desktop production management tool was determined to be the best course of action during the project's discovery and analysis phase. Multiple users would be able to access the system from various locations using the web-based solution and conduct commercial operations. This system would make it simple for the corporate office to access the most recent store information and carry out system maintenance tasks.

Managers would benefit greatly from the Production management system since it would make it easier for them to identify things that need to be ordered first. As a result, managers would spend significantly less time on production management tasks and considerably more time managing the day-to-day operations of the store. The store managers could also ask for the transfer of goods from nearby retailers to meet an urgent need. As a result, the company would experience improved customer service and customer happiness, which would raise its income.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Tools Used:

The project development started after conducting interviews at ZM Corporation to identify their pain points. After this, we decided to use the Waterfall model for our  proposed system development Life Cycle (SDLC) because the proponents really believe that using this model.

•	Node-JS for Backend

•	IDE – Net Beans

•	XAAMP  app for connection of Backend and Frontend

•	Frontend on GUI

•	Database Connection on MySQL

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

## User Interface:

### Login Page
	
<img width="729" alt="Screenshot_20221201_012916" src="https://user-images.githubusercontent.com/76508613/211358495-68330084-0eac-402c-893e-156c3a439872.png">


o Working

	 Database is connected behind the scenes for the login page.

	 When a user enters his/her credentials, they are checked in the database for verification

	 If the Email and Password matches correctly, a pop-up is displayed saying “Username and Password Matched”

	 If Email and Passwords were incorrect, a pop-up is displayed saying
  	“Incorrect Username and Password”
  
o How to Use It:

	 To, type in your Email and Password, first clear the text on the dialog box

	 After credentials are added, click the login button.

	 A pop-up menu will open.

	 On Pressing okay, the dashboard will become visible

### Dashboard

<img width="884" alt="Screenshot_20221201_013805" src="https://user-images.githubusercontent.com/76508613/211359411-7cad58d4-c313-4606-acb8-b504db5d55d3.png">

o Working

	 Clicking on any side menu option, will redirect you to it’s page.
	
	 Clicking on add user, will direct to a new page, asking to enter information to create a new user
	
	 Clicking on logout, will close the dashboard and will move you out of the system and back to the login page
	
	 NOTE: Option More, is right not in this version.
	
o How To Use It:

	 Different Tabs could be accessed by just clicking on the icon with the cursor of the mouse.
	
	 Click on the search bar to type, what you want to search
	
### Add Users
 
 ![Screenshot_20221201_081729](https://user-images.githubusercontent.com/76508613/211359918-a987dae7-548e-45b2-8c92-02507b06606b.png)

o Working: 

	 Data is collected from all the fields and stored in an array.
	
	 Pressing “Add User” button, Array block is passed to a function, which executes an “INSERT” query to enter all the data into the table.
	
 	 Email, Password and Role are extracted separately and are passed to the ‘logincredentials’ table to create Email and Password for login.

o How To Use It:

 	 Fill all the details in the text fields and select option through the drop-down menu.
	
	 Don’t leave any field marked with (*) in the heading.
	
	 Press “Add User”, to create user credential and store all the entries in the database.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
	
## Note: 

Document has been attached for compltet details and overview of the project.


