# TEnmo - Peer-to-Peer Money Transfer Application

TEnmo is a simple command-line application that simulates a peer-to-peer money transfer system. Users can register, log in, view account balances, and send or request virtual currency between accounts. The application includes a RESTful API backend built with Spring Boot and a PostgreSQL database.

## Features

- User registration and authentication (Spring Security)
- View account balance
- Send and request "TE Bucks" to/from other users
- Approve or reject pending transfer requests
- Transaction history and transfer details
- CLI interface to interact with the system

## Technologies Used

- **Java**
- **Spring Boot**
- **Spring Security**
- **Spring Data JPA**
- **PostgreSQL**
- **RESTful API**
- **JUnit** (for testing)
- **Maven**
- **IntelliJ IDEA**

## Architecture

- **Backend:** RESTful API built with Spring Boot
- **Database:** PostgreSQL with schema and DAO layers
- **Frontend:** Command-Line Interface (CLI) in Java

## Getting Started

### Prerequisites

- Java 17+
- PostgreSQL
- Maven
- IntelliJ IDEA or any Java IDE

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Shamar090/tenmo.git
   cd tenmo
