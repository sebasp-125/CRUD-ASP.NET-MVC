
# 👥 User Management System

A simple **CRUD (Create, Read, Update, Delete)** application for user management, built with **ASP.NET MVC**, **Entity Framework**, and **LINQ**.  
This project follows the **Repository Pattern** and connects to **SQL Server** for data storage.

## 📌 Features
✅ Add, edit, delete, and view users  
✅ Uses **Entity Framework** for database interactions  
✅ Implements the **Repository Pattern** for better code organization  
✅ Connected to **SQL Server**  

---

## 🚀 Installation & Setup

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/yourusername/your-repo.git
cd your-repo
```

### 2️⃣ Install dependencies  
Make sure you have **.NET SDK** installed. Then, restore the dependencies:  
```bash
dotnet restore
```

### 3️⃣ Set up the database  
The SQL Server database is included in the repository. You just need to:  
1. Open **SQL Server Management Studio (SSMS)**  
2. Restore the database backup file (`users_db.bak`)  
3. Update the **connection string** in `appsettings.json`:  
   ```json
   "ConnectionStrings": {
     "DefaultConnection": "Server=YOUR_SERVER;Database=users_db;Trusted_Connection=True;"
   }
   ```

### 4️⃣ Run the project  
```bash
dotnet run
```
Then open **http://localhost:5000** in your browser! 🎉  

---

## 🛠️ Technologies Used
- **ASP.NET MVC** 🌐  
- **Entity Framework** 🗄️  
- **LINQ** 📊  
- **SQL Server** 💾  
- **Bootstrap** 🎨  

---

## 📄 License
This project is open-source and available under the **MIT License**.  

---

💡 *Feel free to contribute! Fork the repo and submit a pull request!* 🚀  
