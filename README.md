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
docker run --name vudp-postgres-db -e POSTGRES_USER=vudp-user -e POSTGRES_PASSWORD=placeholder -e POSTGRES_DB=vudp -p 5434:5432 -v pgdata:/var/lib/postgresql/data -d postgres:17
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


