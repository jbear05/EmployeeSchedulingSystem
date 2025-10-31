# Employee Scheduling System

A full-stack web application for managing employees, shifts, and assignments. Built with Spring Boot and React.

## 🏗️ Architecture

This project follows a microservices architecture with separate frontend and backend repositories:

- **Backend API**: [employee-scheduling-backend](https://github.com/jbear05/employee-scheduling-backend)
  - RESTful API built with Spring Boot
  - Java, Spring Data JPA, (H2 currently for development, PostgreSQL soon)
  
- **Frontend UI**: [employee-scheduling-frontend](https://github.com/YOUR_USERNAME/employee-scheduling-frontend)
  - Modern React SPA with React Router
  - JavaScript/React, Axios, date-fns

## ✨ Features

- **Employee Management**: Create, edit, and delete employee records with role assignments
- **Shift Templates**: Define reusable shift templates with time ranges and role requirements
- **Weekly Calendar View**: Visual schedule grid showing all assignments for the week
- **Assignment Management**: Assign employees to shifts on specific dates
- **Navigation**: Browse through weeks with previous/next/today controls

## 🚀 Getting Started

### Prerequisites
- Node.js 16+ and npm
- Java 21
- PostgreSQL database

### Quick Start

1. **Clone both repositories:**
```bash
   git clone https://github.com/YOUR_USERNAME/employee-scheduling-backend.git
   git clone https://github.com/YOUR_USERNAME/employee-scheduling-frontend.git
```

2. **Start the backend:**
```bash
   cd employee-scheduling-backend
   # Configure application.properties with your database credentials
   ./mvnw spring-boot:run
```
   Backend will run on `http://localhost:8080`

3. **Start the frontend:**
```bash
   cd employee-scheduling-frontend
   npm install
   npm run dev
```
   Frontend will run on `http://localhost:5173`

## 📸 Screenshots

UI screenshots coming soon

## 🛠️ Tech Stack

### Backend
- Spring Boot 3.5.7
- Spring Data JPA
- MySQL/PostgreSQL
- Maven

### Frontend
- React 18
- React Router 6
- Axios
- date-fns
- Vite

## 📋 API Documentation

See the [backend repository](https://github.com/YOUR_USERNAME/employee-scheduling-backend) for detailed API endpoints.

## 👤 Author

Jair Garcia Fonseca
- LinkedIn: [https://linkedin.com/in/jairg](https://www.linkedin.com/in/jair-garcia-fonseca/)
