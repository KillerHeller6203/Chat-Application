## Chat Application
A full-stack real-time chat application built using Spring Boot for the backend and a modern JavaScript frontend.
The project demonstrates real-time communication, authentication, and RESTful API design.

--- 

## Overview:
This project is a real-time chat application that allows users to communicate instantly through a web interface.
It follows a separation of concerns architecture with independent backend and frontend modules.
The application is structured to showcase backend development skills using Spring Boot, REST APIs, WebSocket-based communication, and frontend integration.

---

## Tech Stack:

## Backend
- Java
- Spring Boot
- Spring Web
- Spring Security
- WebSockets
- Maven
- REST APIs

## Frontend:
- JavaScript
- Modern frontend tooling (bundler-based setup)
- HTTP/WebSocket communication with backend

---

## Project Structure:
```
Chat-Application/
│
├── realtime-chat-backend/
│   ├── src/
│   ├── pom.xml
│   └── application configuration
│
├── realtime-chat-frontend/
│   ├── src/
│   ├── public/
│   └── frontend configuration files
│
└── README.md
```

---

## Features:
- Real-time messaging using WebSockets
- Backend REST APIs for application logic
- Modular backend and frontend structure
- Scalable architecture suitable for extension
- Clear separation between client and server

---

## How It Works:
- The backend exposes REST endpoints and WebSocket connections.
- Clients connect to the backend through HTTP/WebSockets.
- Messages are transmitted in real time between connected users.
- Spring Boot handles request routing, security, and application lifecycle.

---

## Setup Instructions:
## Backend
```bash
cd realtime-chat-backend
```
```bash
.\mvnw clean compile
```
```bash
./mvnw spring-boot:run
```

## Frontend:
```bash
cd realtime-chat-frontend
```
```bash
npm install
```
```bash
npm run dev
```

---

## Learning Outcomes:
- Hands-on experience with Spring Boot application structure
- Understanding real-time communication using WebSockets
- Designing RESTful APIs
- Integrating frontend and backend services
- Managing multi-module projects in Git
