📄 Available in: [English](README.en.md) | [Português](README.md)

# 🛡️ RPG Web API (.NET Core)

This project is a RESTful API developed in ASP.NET Core with the goal of simulating a role-playing game (RPG) character management system. It was built as a study and demonstration project, following best practices and typical .NET application structure.

## 🚀 Technologies Used

- ASP.NET Core Web API
- C#
- Entity Framework Core
- Swagger for API documentation
- REST architecture

## 📂 Project Structure

The project follows a clean and organized folder structure for easy understanding and maintenance:

- `Controllers/` – Defines the endpoints and handles HTTP requests.
- `Models/` – Contains the domain models and data structures.
- `Services/` – Implements the business logic of the application.
- `Data/` – Handles the database context and migrations.
- `Program.cs / Startup.cs` – App initialization and configuration.

## 📦 Features

- Create, read, update, and delete RPG characters
- Attribute configuration: strength, defense, intelligence
- Basic class system (e.g., knight, mage)
- Damage calculation logic
- API documentation with Swagger UI

## 🧪 How to Run

1. Clone the repository  
2. Open the solution in Visual Studio or VS Code  
3. Restore dependencies using `dotnet restore`  
4. Run the application using `dotnet run` or your IDE  
5. Access Swagger UI at `http://localhost:5000/swagger`

## 🎯 Purpose

This project was developed for learning purposes and as a portfolio demonstration of backend development skills using C# and ASP.NET Core.

