# 🎓 Student Portal Web Application

An **ASP.NET Core web application** built using **ASP.NET Core MVC** and **Entity Framework Core**.

## Technologies Used

- ASP.NET Core
- ASP.NET Core MVC
- Entity Framework Core
- SQL Server
- C#
- Bootstrap

## Installation

1. Clone the repository

git clone https://github.com/Clairazi/StudentPortalWebApp.git

2. Navigate to the project folder

cd StudentPortal.Web

3. Restore dependencies

dotnet restore

4. Update the database

dotnet ef database update

5. Run the application

dotnet run

## Running the App

After running the project, open your browser and go to:

https://localhost:7189

## Database

This project uses **Entity Framework Core** with **SQL Server**.

To create migrations:

dotnet ef migrations add InitialCreate  
<<<<<<< HEAD
dotnet ef database update
=======
dotnet ef database update
>>>>>>> 92ad67ec0b991f52111c1ac11249f9f6932356a8
