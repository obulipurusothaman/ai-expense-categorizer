# AI Expense Categorizer

A full-stack web application that automatically categorizes your expenses using keyword-based AI classification.

## Tech Stack
- **Backend:** Java, Spring Boot, Spring Data JPA, H2 Database, Maven
- **Frontend:** React.js, Axios, CSS

## Features
- Add expenses with description and amount
- Auto-categorizes into Food, Travel, Bills, Shopping, Health, Others
- Filter expenses by category
- Live total and count stats
- H2 in-memory database

## How to Run

### Backend
```bash
cd backend
mvn spring-boot:run
```
Runs on http://localhost:8080

### Frontend
```bash
cd frontend
npm install
npm start
```
Runs on http://localhost:3000

### Database Console
Visit http://localhost:8080/h2-console
- JDBC URL: `jdbc:h2:mem:testdb`
- Username: `SA`
- Password: *(leave blank)*

## API Endpoints
| Method | URL | Description |
|--------|-----|-------------|
| GET | /api/expenses | Get all expenses |
| POST | /api/expenses | Add new expense |

## Project Structure
