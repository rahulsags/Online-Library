# Online-Library

## Overview

This project is a Library Management System built using Django and Django Ninja. It allows users to view books, borrow them, and return borrowed books. The system includes user management with custom user attributes.

## Features

- **User Management**: Users can sign up, log in, and manage their profiles.
- **Book Management**: View a list of available books and their details.
- **Borrowing System**: Borrow books if they are available and return them when done.

## Technologies Used

- Django
- Django Ninja
- SQLite (default database)

## Project Structure

- **users/**: Contains user-related models, views, and authentication.
- **books/**: Manages book-related models and views.
- **borrowing/**: Handles the borrowing and returning of books.

## Setup and Installation

### Prerequisites

- Python 3.x
- Django
- Django-Ninja
- pip

### Clone the Repository

```bash
git clone https://github.com/rahulsags/Online-Library.git
cd elevate

```bash
python -m venv venv
venv\Scripts\activate

```bash
pip install -r requirements.txt

```bash
python manage.py migrate

```bash
python manage.py runserver
 
