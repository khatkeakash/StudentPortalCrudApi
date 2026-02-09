Student CRUD API – ASP.NET Core Web API

This is a simple Student Management CRUD API built using ASP.NET Core Web API and Entity Framework Core.
The API allows users to create, read, update, and delete student records from a SQL Server database.

🚀 Features

Create new student

Get all students

Get student by ID

Update student details

Delete student record

RESTful API structure

Entity Framework Core integration

🛠️ Technologies Used

ASP.NET Core Web API

C#

Entity Framework Core

SQL Server

Swagger (API testing)

📂 Project Structure
StudentCrudApi
│
├── Controllers
│   └── StudentController.cs
│
├── Models
│   ├── Student.cs
│   └── StudentDbContext.cs
│
├── Program.cs
├── appsettings.json

📌 API Endpoints
Method	Endpoint	Description
GET	/api/Student	Get all students
GET	/api/Student/{id}	Get student by ID
POST	/api/Student	Add new student
PUT	/api/Student/{id}	Update student
DELETE	/api/Student/{id}	Delete student
