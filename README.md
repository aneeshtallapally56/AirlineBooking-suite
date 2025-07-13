# ✈️ Airline Booking Microservices System

A professional-grade microservices backend architecture simulating real-world concurrency, DBMS, and system design challenges.

##  Microservices Overview

-  **Search Service** – Flights lookup and querying
-  **Booking Service** – Handles booking, payments, and transactional integrity
-  **API Gateway** – Central entrypoint with auth, rate limiting, and proxy routing

## ⚙ Tech Stack

- Node.js, Express.js
- MySQL, Sequelize ORM
- RabbitMQ for messaging
- REST APIs
- Docker (optional)

##  Key Features

- Decoupled services using message queues (RabbitMQ)
- Transaction-safe booking with DB-level isolation
- API Gateway for unified access and authentication
- Race condition mitigation and rollback strategies

##  Repositories

- [Booking Service](https://github.com/aneeshtallapally56/Airline-Booking-Service)
- [Search Service](https://github.com/aneeshtallapally56/Airline-Search-Service)
- [API Gateway](https://github.com/aneeshtallapally56/API-Gateway)

---

> For a complete walkthrough and deployment instructions, visit each individual repo.
