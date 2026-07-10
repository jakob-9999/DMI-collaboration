# DMI Application

This project is a collaboration with DMI (Danish Meteorological Institute) as part of their VUDP project. The goal was to develop a full-stack application for retrieving, storing, and visualizing precipitation and sewer data.

The purpose of the project was to gain practical experience with full-stack development, including backend development, databases, APIs, and frontend visualization.

## Features

- Retrieve weather and sewer data from APIs
- Store precipitation and sewer data in a database
- Frontend visualization of weather and sewer data

## Technologies

### Backend
- Java
- Spring Boot
- PostgreSQL
- Docker

### Frontend
- React
- Vite

## Running the Project

Install:

- Java JDK
- Maven
- Docker
- Node.js and npm

## 1. Start the database

Start PostgreSQL using Docker:

```bash
docker run --name dmi-postgres \
-e POSTGRES_USER=<username> \
-e POSTGRES_PASSWORD=<password> \
-e POSTGRES_DB=<database-name> \
-p 5432:5432 \
-d postgres
```
## 2. Start the server

```bash
cd server
mvn spring-boot:run
```

## 3. Start the client

```bash
cd client
```

Install dependencies:

```bash
npm install
```

Start Vite:
```bash
npm run dev
```


