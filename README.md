.NET Core Web API Project

This is a simple Web API built using ASP.NET Core and Microsoft SQL Server. It demonstrates the use of RESTful endpoints for performing CRUD operations with a SQL Server database using Entity Framework Core.

🔧 Technologies Used

- ASP.NET Core (.NET 8 )
- Entity Framework Core
- Microsoft SQL Server
- Visual Studio 2022
- Swagger (for API testing)
- Git for version control

🚀 Features

- CRUD operations using RESTful API
- SQL Server database integration using a connection string
- Swagger UI for API testing


🛠️ Getting Started

Follow these steps to run this project locally:

1. Clone the Repository

use git bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name

2. Open in Visual Studio
Open the .sln file in Visual Studio.

3. Set Up the Database
Make sure Microsoft SQL Server is running.

Create a new database manually (if not using migrations).

Or run EF Core migrations to set up the database:

In the Package Manager Console run
Update-Database

Make sure the connection string in appsettings.json matches your SQL Server setup:

4. Run the Application
Press F5 or click Start Debugging in Visual Studio.

Navigate to test the API with Swagger.

