son olarak projenin readmi dosyasını güncelledim : # AI-Supported Patient Tracking Platform (Lite)

A simple patient tracking application developed as a short case study.  
The project demonstrates a basic full-stack setup using Angular and .NET 8 Web API with JWT authentication.

---

## Tech Stack

**Backend**
- .NET 8 (ASP.NET Core Web API)
- Entity Framework Core
- PostgreSQL
- JWT Authentication
- Swagger

**Frontend**
- Angular 18
- TypeScript
- Reactive Forms
- Angular Router
- HttpClient

---

## Features

- JWT-based login and route protection
- Patient list and patient detail views
- Create and delete patient records
- Medical history display (sample data)
- Mock AI prediction result returned from backend
- Logout functionality

---

## Project Structure

- Backend: Controllers, Services, EF Core, seeded sample data
- Frontend: Feature-based Angular structure with guards and interceptors

---

## Running the Project

### Backend
```bash
cd case1
dotnet restore
dotnet run
http://localhost:5149/swagger
cd case1-frontend
npm install
npm start
Frontend `http://localhost:4200` 
{
  "username": "doctor1",
  "firstName": "Ali",
  "lastName": "Başkan",
  "dateOfBirth": "1980-06-15",
  "password": "password123"
}
— Aslınur Şevval Sezgin  
Thank you for reviewing this project.
 :=)  