# Swasthya Setu

A comprehensive healthcare platform that connects patients, doctors, and hospitals. It provides:

- **Appointment booking** with payment-first token generation
- **AI symptom checker** powered by Gemini models
- **Admin dashboards** for analytics and management
- **Patient portal** for medical records, financial ledgers, and more

## Tech Stack

- **Backend**: Django (Python) with SQLite (development) / MongoDB
- **Frontend**: Vite + React (JavaScript/JSX) with modern UI components
- **AI**: Gemini models for symptom analysis
- **Styling**: CSS modules and custom design system

## Getting Started

```bash
# Clone the repo
git clone https://github.com/RajKhaitan3/SwasthyaSetu.git
cd SwasthyaSetu

# Backend setup
python -m venv venv
source venv/bin/activate  # on Windows: venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

# Frontend setup
cd frontend
npm install
npm run dev
```

## Contributing

Feel free to open issues or submit pull requests. Follow the contribution guidelines and ensure code passes the CI checks.

## License

This project is licensed under the MIT License.
