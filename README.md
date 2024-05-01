# MyBankingApp

MyBankingApp is a web application developed as a class project to demonstrate web security principles. It is built using Flask and implements various security measures to prevent common vulnerabilities such as XSS, CSRF, SQL Injection, and user enumeration.

In addition to the basic functionalities covered in class, MyBankingApp includes the following features:

- Transfer functionality
- User enumeration defense
- Fun animations for displaying and transferring virtual trading cards

## Technologies Used

- Flask
- MongoDB
- JWT (JSON Web Tokens) for authentication
- PBKDF2 for password hashing
- HTML
- CSS
- Python

## Security Measures Implemented

- Passwords are securely hashed using PBKDF2.
- JWTs are stored in cookies for authentication.
- XSS protection is implemented by sanitizing user inputs and escaping output.
- CSRF protection is implemented using CSRF tokens.
- SQL Injection is prevented by using parameterized queries.
- User enumeration is defended against by consistent error messages for login and registration.

## Getting Started

To run this application locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/Brandonb29/LMUBankingApp.git

