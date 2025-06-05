# Product CRUD Example

This project demonstrates a minimal CRUD of products using Django for the backend API and React for a very small frontend.

## Backend setup

1. Create a Python virtual environment and install dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r backend/requirements.txt
```

2. Run migrations and start the development server:

```bash
cd backend
python manage.py migrate
python manage.py runserver
```

The API will be available at `http://localhost:8000/api/products/`.

## Frontend

Open `frontend/index.html` in your browser. It uses React via CDN and communicates with the backend API to perform CRUD operations.
