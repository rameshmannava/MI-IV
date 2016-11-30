# Project	:	Church Financial Record Keeping
# Client	:	Mrs. Cerise Wuthrich
# Team		:	MI IV (Ramesh Mannava,Divya Shree HB,Majesh Reddy Salla,Clive Matiku)
# Course	:	CMPS 5153 Advanced Software Engineering
# Professor	:	Dr.Catherine Stringfellow

------------------------------------------------------------------------------------------
# This file shows the contents included in CD
------------------------------------------------------------------------------------------

# Database Creation
	
	This folder contains Church Finance.sql file to setup database for the application.
	
# Documents

	This folder contains sub folders which contain all documents regarding the project.
		
		Folders:
		
		# Design
		
			This folder conatins design document for the application.
			
		# Minutes
		
			This folder contains minutes document about all meetings between team members about project.
			
		# Objective Grading Sheet
		
			This folder conatins project objective grading sheet.
			
		# Project Plan
			
			This folder conatins project plan document.
			
		# Report
		
			This folder conatins final report about the project.
			
		# Requirements
		
			This folder conatins application requirements document.
			
		# Test Plan
			
			This folder conatins project test plan document.
			
		# User Manual
		
			This folder conatins application user manual.
			
# Jars Required

	This folder conatins jars that are required to run the application.
	
# Presentations

	This folder conatins project presentations(interim and final).
	
# Softwares

	This folder conatins softwares that are required for the application
	
		1. Apache Tomacat Server
		2. Eclipse
		3. MYSQL Software
		4. MYSQL Workbench Tool(GUI to connect to MYSQL database).
		
# Source Code
	
	This folder conatins the source code of the application.
	
# WAR File

	This folder conatins war file of the project that is used to setup the application 
	directly in to the system.
	
------------------------------------------------------------------------------------------------------------------------

# Project Installation Procedure

	The application developed on java, So the system should have java(1.6 or 1.7) to be installed
	
	-> Copy all softwares in to the system from CD.
	
	-> Install MYSQL software(Please remember password what you gave while installing).
	
	-> Install MYSQL Workbench
	
	-> Open MYSQL Workbench and it will prompt for password. Provide password what you gave while installing.
	
	-> Copy the content(Commands) from ChurchFinance.sql and run it in command window to create database.
	
	-> Once database is ready go to the eclipse folder and double click on eclipse.exe icon. It will
	   open the eclipse and ask for workspace. Select folder where you need to setup application.
	   
	-> After eclipse opened right click on click this link to create new server.
	
	-> In the server window Apache -> Tomacat7.0 -> Next -> Browse the Tomacat location(where you copied in to your system) -> Finish
	
	-> Once Server installed right click on Project Explorer window on left hand side and go to
		Import -> WAR File -> Browse the WAR File in your System that is already copied -> Finish
		
	-> Once application installed you can see that in project explorer. Right click on project and 
		Run As -> Run on Server
		
	-> Next, It will open the browser in eclipse. Copy the URL from the browser url bar and try that 
	   URL in Google Chrome(username : wuthrich,password : secretary).