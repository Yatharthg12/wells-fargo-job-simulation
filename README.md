# Wells Fargo Software Engineering Simulation - Task 2

## Project Overview
This repository contains the implementation of a data model for a Financial Advisor Management System. The system is designed to allow financial advisors to manage their clients, track portfolios, and monitor individual securities.

## Tech Stack
* **Language:** Java 17
* **Framework:** Spring Boot 3.x
* **ORM:** Spring Data JPA
* **Database:** H2 (Relational)

## Data Model
The system architecture follows a relational structure:
* **FinancialAdvisor**: Manages multiple clients.
* **Client**: Assigned to one advisor and owns one portfolio.
* **Portfolio**: A container for a client's financial assets.
* **Security**: Individual assets within a portfolio containing data for name, category, purchase date, price, and quantity.

## Key Features
* Automated ID generation for all entities.
* Defined One-to-Many, Many-to-One, and One-to-One relationships.
* JPA annotations for database schema mapping.
* Scalable architecture designed for high-uptime requirements.
