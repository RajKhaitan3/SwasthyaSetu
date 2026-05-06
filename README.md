# Swasthya Setu 🏥

A full-stack Hospital Management Web Application that connects 
patients, doctors, and hospital administrators on a single platform.

## Features

- 📅 **Appointment Booking** — Payment-first token generation system
- 👤 **Patient Portal** — Medical records and financial ledger management  
- 📊 **Admin Dashboard** — Analytics and hospital management tools
- 🔐 **Role-based Access** — Separate flows for patients, doctors, and admins

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React (Vite), JavaScript, CSS |
| Backend | Django (Python) |
| Database | SQLite (dev) / PostgreSQL (prod) |

## Getting Started

```bash
# Clone the repo
git clone https://github.com/RajKhaitan3/SwasthyaSetu.git
cd SwasthyaSetu

# Backend setup
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

# Frontend setup
cd frontend
npm install
npm run dev
```

## Status

🚧 Actively in development — features are being improved and expanded.

## License

MIT License
