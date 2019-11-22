# PhonebookApplication
PhonebookApplication
Consists of a rest api and mvc front end.
  - Get's a list of phonebook entries and displays it to the user
  - User can add an entry to the phonebook

Technologies and frameworks used:
  - .Net Framework 4.72
  - .Net Core 3.0
  - MVC
  - AutoMapper
  - Nlog for logging that I added to the api controller only.
  - NUnit for Unit Tests
  - Unity for dependecy injection
  - Bootstrap, javascript and jquery 

Getting Started
  - Restore the backup of the database (DigitalTech.bak) in Microsoft SQL Server Management Studio
  - Open the solution and go to the following project "PhonebookApplication.API" and update the ConnectionStrings (DigitalTechConnection) in the 		appsettings.json file by replacing the "Data Source" with your sql instance.

Running application
  - Make sure "Multiple Startup Projects" are selected to run the application.
  - The api key should point to the localhost location of the api, which can be found in the web.config of the WebUI

