# Nimap Test Project

![Django Logo](https://www.djangoproject.com/m/img/logos/django-logo-negative.png)
![Django REST Framework Logo](https://www.django-rest-framework.org/img/logo.png)

## Setup Instructions

1. Navigate to the project directory:
    ```bash
    cd nimap_test
    ```

2. Create a virtual environment:
    ```bash
    python3 -m venv venv
    ```

3. Activate the virtual environment:
    ```bash
    source venv/bin/activate
    ```

4. Install project dependencies:
    ```bash
    pip3 install -r requirements.txt
    ```
2. Create a virtual environment:
    ```bash
    Uses a Postgres Database As per Documentation
    ```
5. Apply database migrations:
    ```bash
    python3 manage.py makemigrations
    python3 manage.py migrate
    ```
    
6. Run the development server:
    ```bash
    python3 manage.py runserver
    ```

## API Endpoints

- Clients: [http://localhost:8000/api/clients/](http://localhost:8000/api/clients/)
- Projects: [http://localhost:8000/api/projects/](http://localhost:8000/api/projects/)
