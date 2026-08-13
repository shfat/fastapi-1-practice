# University Data Validation API

A lightweight **FastAPI-based validation service** built for practicing backend development concepts and implementing structured data validation logic.

This project focuses on validating student-related data using custom rules and FastAPI request handling.

---

## Purpose of the Project

This project was developed as a **learning and practice exercise** to strengthen backend development skills, including:

- FastAPI fundamentals
- Input validation logic design
- Working with Pydantic models
- Handling API requests and responses
- Error management in backend systems

---

## Features

This API validates multiple student-related fields, including:

- Student ID format and structure validation
- Name validation (Persian characters only)
- Birthdate format and logical validation
- National ID validation using checksum algorithm
- Mobile phone number validation
- Landline phone format validation
- Postal code validation
- Address length validation
- Faculty validation
- Major validation
- Province and city validation
- Marital status validation
- Birth certificate serial validation

---

## Tech Stack

- Python 3
- FastAPI
- Pydantic

---

## API Endpoint

### POST `/validate`

This endpoint receives a JSON object containing student data and returns:

- A list of validation errors (if any exist)
- A success message if all inputs are valid

---

## Project Notes

- This project is a **practice-level backend service**
- Focus is on data validation logic and API structure

---

## Author

Computer Engineering student interested in backend development and software engineering.
