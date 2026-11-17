# Patient Management System using FastAPI

## Overview

This repository contains my hands-on learning and practice with **FastAPI**, a modern, fast Python web framework for building APIs.

The project demonstrates fundamental FastAPI concepts, including API routing, HTTP methods, path parameters, query parameters, request validation, Pydantic models, and CRUD operations.

## Technologies Used

- Python
- FastAPI
- Pydantic
- Uvicorn
- JSON

## Features

- Create and manage patient records.
- Retrieve all patient information.
- Retrieve individual patients by ID.
- Update patient information.
- Delete patient records.
- Calculate BMI automatically.
- Categorize patients based on BMI.
- Sort patients by height, weight, and BMI.
- Validate request data using Pydantic.
- Handle HTTP exceptions and errors.
- Interactive API documentation using Swagger UI.

## Project Structure

```text
FastAPI-Basic/
│
├── main.py
├── patients.json
├── requirements.txt
├── README.md
└── .gitignore
```

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/FastAPI-Basic.git
```

### 2. Navigate to the Project Directory

```bash
cd FastAPI-Basic
```

### 3. Create a Virtual Environment

```bash
python3 -m venv venv
```

### 4. Activate Virtual Environment

**macOS / Linux**

```bash
source venv/bin/activate
```

**Windows**

```bash
venv\Scripts\activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the Application

```bash
uvicorn main:app --reload
```

The application will run at:

```text
http://127.0.0.1:8000
```

## API Documentation

FastAPI automatically generates interactive API documentation.

**Swagger UI:**

http://127.0.0.1:8000/docs

**ReDoc:**

http://127.0.0.1:8000/redoc

## API Endpoints

| HTTP Method | Endpoint | Description |
|---|---|---|
| GET | `/` | Welcome message |
| GET | `/about` | API information |
| GET | `/view` | View all patients |
| GET | `/patient/{patient_id}` | View patient by ID |
| GET | `/sort` | Sort patient records |
| POST | `/create` | Create a patient |
| PUT | `/edit/{patient_id}` | Update patient |
| DELETE | `/delete/{patient_id}` | Delete patient |

## Concepts Learned

- FastAPI Application Setup
- API Routing
- HTTP Methods
- Path Parameters
- Query Parameters
- Pydantic BaseModel
- Data Validation
- Computed Fields
- JSON File Handling
- CRUD Operations
- Exception Handling
- HTTP Status Codes
- Swagger Documentation

## Future Learning Goals

- Database Integration with PostgreSQL
- SQLAlchemy ORM
- JWT Authentication
- API Security
- Middleware
- Dependency Injection
- API Testing with Pytest
- Docker and Deployment

## Author

Computer Science & Engineering Graduate

Interested in Backend Development, Python, FastAPI and Machine Learning.

## License

This project is intended for educational and learning purposes.
