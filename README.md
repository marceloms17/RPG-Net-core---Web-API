📄 Disponível em: [Português](README.md) | [English](README.en.md)

# 🛡️ RPG Web API (.NET Core)

Este projeto é uma API REST desenvolvida em ASP.NET Core com o objetivo de simular um sistema de personagens de RPG. Foi construído como projeto de estudo e demonstração, seguindo boas práticas e estrutura típica de aplicações .NET.

---

## ⚙️ Tecnologias Utilizadas

- ASP.NET Core Web API
- C# 8.0+
- Entity Framework Core (simples)
- JSON Configuration (`appsettings.json`)
- Swagger (pode ser adicionado para documentação)
- Visual Studio / VS Code

---

## 📂 Estrutura do Projeto

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

## 🚀 Como Executar

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/RPG-Net-core---Web-API.git
```

2. Restaure os pacotes:
```bash
dotnet restore
```

3. Execute o projeto:
```bash
dotnet run
```

4. Acesse a API em:
```
https://localhost:5001/api/Character
```

---

## 📌 Funcionalidades Simuladas

- Criar e listar personagens
- Definir atributos como força, inteligência e defesa
- Uso de enums para classes de personagem (Mage, Knight, Cleric, etc.)

---

## 📁 Observações

- Projeto com fins educacionais, criado para praticar a estruturação de APIs REST com C#
- Pode ser expandido com autenticação, banco de dados e documentação Swagger futuramente

---

## 👤 Autor

Marcelo Morais dos Santos  
📧 marceloms17@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/marcelo-morais-61584146)
