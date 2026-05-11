# Enterprise Employee Management System

A full-stack enterprise-style employee management platform built with Angular for the frontend and ASP.NET Core Web API for the backend. This project demonstrates scalable CRUD architecture, form validation, API versioning, DTO-based data flow, AutoMapper integration, Swagger API testing, and database flexibility for enterprise-grade business workflows.

## Scope

This application is designed to extend core development concepts into a structured enterprise project by combining a modern frontend framework with a robust backend API architecture.

### Key Objectives:
- Build a scalable employee management platform  
- Implement responsive UI with Angular forms and validation  
- Develop RESTful APIs using ASP.NET Core  
- Apply API Versioning for maintainability  
- Use DTOs with AutoMapper for secure and structured data transfer  
- Support SQL Server or PostgreSQL database integration  
- Enable Swagger for API endpoint testing  
- Provide a foundation for future enterprise features like authentication and advanced search  

The use of Data Transfer Objects (DTOs) with AutoMapper protects domain entities and creates clean separation between internal database models and external API contracts for operations such as fetching, creating, and updating employee data.

## Development Stack

The application was developed using:

- C# / ASP.NET Core Web API  
- Angular  
- Bootstrap  
- SQL Server / PostgreSQL  
- Swagger (Swashbuckle)  
- AutoMapper  

## Core Features

- Employee CRUD Operations  
- Form Validation  
- Responsive Enterprise UI  
- API Versioning  
- DTO Architecture  
- Swagger API Testing  
- Database Flexibility  
- Structured Backend Architecture  

## Built-in API Endpoint Testing

Swagger is integrated directly into the application for easy endpoint testing and documentation.

After launching locally, navigate to:

https://localhost:5001/swagger

This provides a complete API testing interface for validating endpoints and future integrations.

## Setup Requirements

To run this project locally, install:

- ASP.NET Core SDK  
- Node.js  
- Angular CLI  
- SQL Server or PostgreSQL  

## Installation

### Clone the repository:

git clone <repository-url>

### Navigate to the project root:

cd src/EmployeeManager/

## Client Setup

cd client  
npm install  
npm install -g @angular/cli @angular/core

## Server Setup

cd server  
dotnet restore

## Running the Project

### Frontend

ng build --prod

### Backend

dotnet run

## Open in Browser

https://localhost:5001

## Future Enhancements

- Authorization and Authentication  
- Employee Search by Name  
- Role-Based Access Control  
- Dashboard Analytics  
- ERP-style Workflow Expansion  

## Project Highlights

- Enterprise-style architecture simulation  
- Clean separation of concerns  
- Maintainable DTO-based backend  
- Full-stack integration  
- Scalable business application design  
