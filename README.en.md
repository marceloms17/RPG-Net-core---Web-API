# 🛡️ RPG Web API (.NET Core)

📄 Available in: [English](README.en.md) | [Português](README_RPG_WebAPI.md)

This project is a RESTful API developed in ASP.NET Core designed to simulate a simple RPG character management system. It was built as a demonstration and learning project, following best practices and typical .NET structure.

---

## ⚙️ Technologies Used

- ASP.NET Core Web API
- C# 8.0+
- Simple in-memory model (no database)
- JSON Configuration (`appsettings.json`)
- Swagger (optional for documentation)
- Visual Studio / VS Code

---

## 📂 Project Structure

```
├── Controllers/
│   ├── CharacterController.cs
│   └── WeatherForecastController.cs
│
├── Models/
│   ├── Character.cs
│   └── RpgClass.cs
│
├── Program.cs
├── Startup.cs
├── appsettings.json
├── RPG.csproj
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-user/RPG-Net-core---Web-API.git
```

2. Restore packages:
```bash
dotnet restore
```

3. Run the project:
```bash
dotnet run
```

4. Access the API:
```
https://localhost:5001/api/Character
```

---

## 📌 Features

- Create and list RPG characters
- Set attributes like strength, intelligence, and defense
- Use enums for character classes (Mage, Knight, Cleric, etc.)

---

## 📁 Notes

- This project was created for learning purposes
- Future improvements may include authentication, database support, and Swagger UI

---

## 👤 Author

Marcelo Morais dos Santos  
📧 marceloms17@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/marcelo-morais-61584146)
