# Quiz App with React & ASP.NET Core Web API

## Overview

A full-stack Quiz Application developed using React.js and ASP.NET Core Web API. The application allows users to participate in quizzes, answer randomly generated questions, and view their final scores. Quiz results are stored and managed through a SQL Server database.

## Features

- User-friendly quiz interface built with React.js
- Randomized question generation for every quiz attempt
- Multiple-choice questions with interactive UI
- Real-time score calculation and result tracking
- Participant performance and quiz history management
- RESTful API integration between frontend and backend
- Responsive design using Material UI

## Technologies Used

### Frontend

- React.js
- Material UI (MUI)
- Axios
- React Router DOM
- HTML5
- CSS3

### Backend

- ASP.NET Core 6 Web API
- Entity Framework Core
- C#

### Database

- SQL Server

### Tools

- Git
- GitHub
- Visual Studio
- VS Code

## Project Architecture

Frontend (React.js) communicates with ASP.NET Core Web API through REST endpoints. The API manages quiz questions, participant details, score calculation, and database operations using Entity Framework Core and SQL Server.

## Key Functionalities

- Fetch random quiz questions from database
- Submit quiz answers
- Calculate participant score
- Store quiz results in SQL Server
- Manage participant records through Web API

## Installation

### Frontend

```bash
npm install
npm start
```

### Backend

```bash
dotnet restore
dotnet run
```

Configure SQL Server connection string in the ASP.NET Core application before running the API.

## Learning Outcomes

- Full Stack Web Development
- React Component Architecture
- REST API Development
- Entity Framework Core
- SQL Server Integration
- Client-Server Communication
- CRUD Operations

## Author

Pradeep Pawar
