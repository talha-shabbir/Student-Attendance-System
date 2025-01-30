# Student Attendance Portal 📈🔧🔑

Welcome to the **Student Attendance Portal**! This project is built using **Blazor Server** in a 3-tier architecture, consisting of:

- **Blazor Server App** 🔄
- **Class Library for Models** 🔬
- **Class Library for Data Access Layer (DAL)** 🔌

## Features
- Role-based access control with three roles:
  - **Admin** 🔒
  - **Teacher** 🏫
  - **Student** 🎓
- User-friendly design 🌐
- Responsive interface for mobile, tablet, and desktop 📲💻

## Deployment
The app is deployed and available at:
[Student Attendance Portal Deployment](https://student-attendance-system-7178514c82ba.herokuapp.com/) 🐼

![Student Attendance Portal](https://github.com/user-attachments/assets/810a9ac0-fe5e-45db-9776-a165491c6a4a)

## Role-Based Access Details
### Admin Access
- **Email:** `aitisam11@gmail.com`
- **Password:** `Aitisam@1234`
- Make sure to select the correct role during login! 🔓

### Teacher Access
- Emails for teachers must end with `@teacher.edu`. For example:
```csharp
if (role == "Teacher" && email.EndsWith("@teacher.edu"))
{
    return Task.FromResult(true); // Password validation here
}
```

### Student Access
- Emails for students must end with `@students.au.edu.pk`. For example:
```csharp
if (role == "Student" && email.EndsWith("@students.au.edu.pk"))
{
    return Task.FromResult(true); // Password validation here
}
```

## How to Run the Project Locally
1. Clone the repository:
   ```bash
   git clone git@github.com:talha-shabbir/Student-Attendance-System.git
   ```
2. Open the solution in **Visual Studio**.
3. Set the Blazor Server project as the startup project.
4. Update the connection string in `appsettings.json` to point to your database.
5. Run the application! ⚙️🏋

## Contributing
Contributions are welcome! 📚✨ Feel free to submit issues or pull requests.

---

Enjoy using the **Student Attendance Portal**! 🌐✨
