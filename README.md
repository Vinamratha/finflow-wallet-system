# Finflow Wallet System

A Laravel-based wallet and transaction management application built to demonstrate backend engineering skills, REST API development, authentication, database operations, and financial workflow handling.

---

## Features

- User authentication and authorization
- Wallet balance management
- Add money functionality
- Transaction history tracking
- REST API endpoints
- Form validation and error handling
- Database migrations and seeders
- Docker support for local development
- GitHub Actions workflow support

---

## Tech Stack

- Laravel (PHP)
- MySQL
- Docker
- GitHub Actions
- Blade/Vite
- Laravel Sanctum (Authentication)
- Postman (API testing)

---
## Project Structure
```bash
app/            # Application logic
routes/         # Web and API routes
resources/      # Views and frontend assets
database/       # Migrations and seeders
config/         # Application configuration
public/         # Public entry point
```
---

## Setup Instructions
### Prerequisites
Make sure you have installed:
- PHP 8+
- Composer
- MySQL
- Node.js & npm
- Docker (optional)

### Installation
Clone the repository:
```bash
git clone https://github.com/Vinamratha/finflow-wallet-system.git
cd finflow-wallet-system
```
Install PHP Dependencies:
```bash
composer install
```
Install frontend dependencies:
```bash
npm install
```
Copy environment file:
```bash
cp .env.example .env
```
Generate application key:
```bash
php artisan key:generate
```
Configure your database inside ```bash .env ```
Run migrations:
```bash
php artisan migrate
```
Start the development server
```bash
php artisan serve
```
Run Vite:
```bash
npm run dev
```

### Docker Setup
Build & start containers:
```bash
docker-compose up --build
```
---
## API Endpoints

### Auth
- POST /api/register
- POST /api/login

### Wallet
- GET /api/wallet
- POST /api/wallet/add

### Transactions
- POST /api/transfer
- GET /api/transactions

---
## Future Improvements
- Unit and feature testing
- JWT authentication
- Role-based access control
- Email notifications
- Payment gateway integration
- Transaction export functionality
- API rate limiting
- CI/CD deployment pipeline
- Admin dashboard
---
## Learning Objectives
This project was created to strengthen skills in:
- Laravel backend development
- REST API design
- Database schema design
- Authentication and authorization
- Dockerized local environments
- GitHub workflow automation
---
## Author
Backend Engineer with experience in PHP, REST APIs, SQL databases, and enterprise backend systems.

---
## License
This project is for learning and portfolio purposes.
