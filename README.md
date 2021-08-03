# RESTAPI
REST API for the Contact details.

Introduction: 
	-	I have created the CRUD operations for the "Contact" entity using ASP.NET core 3.1
	-	I have used basic authentication to secure the web API. 
	-	Used the XUnit and Moq for the unit test case. 
	- 	Used SQLite as the database for the 
	- 	EntityFrameworkCore

Folder structure.

	FDB.WebAPI
		-	Common
			-	Constants.cs
		-	Controllers
			-	ContactController
		-	DAL
			-	FDBDataContext
		-	Helpers
			-	Common.cs
			-	ExtensionMethods.cs
			-	FDBBasicAuthenticationHandler.cs
		-	Interface
			-	IContactsRepository.cs
			-	IUserRepository.cs 
		-	Model
			-	Contact.cs
			-	User.cs
		-	Repository
			-	ContactRepository.cs
			-	UserRepository.cs
		-	Contact.db
		-	Program.cs
		-	Startup.cs
	FDB.WebAPI.Tests

	
