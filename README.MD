# Food Ordering System – Backend

A backend application for a Food Ordering System built with Python, Django, and Django REST Framework. It provides API services for the React frontend.

## Live Demo

**Backend:** [https://ishratalib.pythonanywhere.com/](https://ishratalib.pythonanywhere.com/)

**Frontend:** [Open Food Ordering System](https://food-ordering-system-123-8ah1kexf0-ishrat-talib.vercel.app/)

## Technologies Used

- Python
- Django
- Django REST Framework
- Django REST Framework Simple JWT
- Pillow
- Django CORS Headers
- drf-yasg
- WhiteNoise
- Gunicorn

## About the Project

This backend is part of a full-stack Food Ordering System developed using React for the frontend and Django REST Framework for the backend. Both applications are maintained in separate repositories and communicate through API integration.

### Project Repositories

- **Frontend Repository:** [Food-Ordering-System](https://github.com/Ishratalib/Food-Ordering-System)
- **Backend Repository:** [Backend-of-Food-ordering](https://github.com/Ishratalib/Backend-of-Food-ordering)

### Run the Complete Project Locally

To run the complete Food Ordering System on your local machine, refer to the README files in both repositories. Follow the frontend README for frontend setup and the backend README for backend setup, dependencies, environment configuration, and execution commands.

## Project Structure

[View Complete Backend Project Structure](https://github.com/Ishratalib/Backend-of-Food-ordering/blob/main/backend-structure.txt)

## Features

- REST API development
- JWT authentication support
- Restaurant and food-ordering functionality
- Frontend API integration
- Media file handling
- API documentation support

## Frontend Integration

The backend provides API services to the React frontend deployed on Vercel.

**Frontend Repository:** [Food-Ordering-System](https://github.com/Ishratalib/Food-Ordering-System)

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Ishratalib/Backend-of-Food-ordering.git
cd Backend-of-Food-ordering
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment in Windows PowerShell:

```powershell
.\venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Configure the required Django settings, secret key, database credentials, and other environment variables according to your project setup.

Do not commit `.env` files or secret credentials to GitHub.

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

The local development server runs at `http://127.0.0.1:8000/`.

## Deployment

- **Backend:** PythonAnywhere
- **Frontend:** Vercel

## Author

**Ishrat Talib**
