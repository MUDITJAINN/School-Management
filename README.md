# School Management API

## Project Overview

This is a simple backend API for managing schools built with **Node.js** and **Express.js**, connected to a **MySQL database hosted on Aiven cloud**. It allows you to:

- Add a new school with details (name, address, latitude, longitude)
- List schools sorted by their distance from a given location

The backend is deployed on **Render.com** for easy remote access and testing.

---

## Platforms and Tools Used

- **Node.js & Express.js** — Backend API  
- **MySQL (Aiven cloud)** — Cloud-hosted MySQL database  
- **Render.com** — Hosting and deployment platform  
- **Postman** — API testing and sharing  
- **Git & GitHub** — Source control and code repository  
- **MySQL Workbench** — Database management and query tool  

## API Endpoints

| Method | Endpoint                                                                 | Description                          |
|--------|--------------------------------------------------------------------------|------------------------------------|
| POST   | https://school-management-3ybf.onrender.com/addSchool                    | Add a new school                   |
| GET    | https://school-management-3ybf.onrender.com/listSchools?latitude=12.97&longitude=77.59 | List schools sorted by location    |

## Postman Collection

Test the API endpoints easily by importing this Postman collection:

[Open Postman Collection](https://www.postman.com/navigation-participant-63326633/school-management-api/collection/1zw8uzo/school-api?action=share&creator=36815307)

